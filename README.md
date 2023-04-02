<!DOCTYPE html>
<html lang="en-US" class="theme-auto">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Sign In - Trustie: Git with trustie</title>
	<link rel="manifest" href="data:application/json;base64,eyJuYW1lIjoiVHJ1c3RpZTogR2l0IHdpdGggdHJ1c3RpZSIsInNob3J0X25hbWUiOiJUcnVzdGllOiBHaXQgd2l0aCB0cnVzdGllIiwic3RhcnRfdXJsIjoiaHR0cHM6Ly9naXRsaW5rLm9yZy5jbi8iLCJpY29ucyI6W3sic3JjIjoiaHR0cHM6Ly9naXRsaW5rLm9yZy5jbi9hc3NldHMvaW1nL2xvZ28ucG5nIiwidHlwZSI6ImltYWdlL3BuZyIsInNpemVzIjoiNTEyeDUxMiJ9LHsic3JjIjoiaHR0cHM6Ly9naXRsaW5rLm9yZy5jbi9hc3NldHMvaW1nL2xvZ28uc3ZnIiwidHlwZSI6ImltYWdlL3N2Zyt4bWwiLCJzaXplcyI6IjUxMng1MTIifV19">
	<meta name="theme-color" content="#6cc644">
	<meta name="default-theme" content="auto">
	<meta name="author" content="Gitea - Git with a cup of tea">
	<meta name="description" content="Gitea (Git with a cup of tea) is a painless self-hosted Git service written in Go">
	<meta name="keywords" content="go,git,self-hosted,gitea">
	<meta name="referrer" content="no-referrer">


	<link rel="icon" href="/assets/img/favicon.svg" type="image/svg+xml">
	<link rel="alternate icon" href="/assets/img/favicon.png" type="image/png">
	<link rel="stylesheet" href="/assets/css/index.css?v=development">
	
<script>
	window.addEventListener('error', function(e) {window._globalHandlerErrors=window._globalHandlerErrors||[]; window._globalHandlerErrors.push(e);});
	window.config = {
		appUrl: 'https:\/\/gitlink.org.cn\/',
		appSubUrl: '',
		assetVersionEncoded: encodeURIComponent('development'), 
		assetUrlPrefix: '\/assets',
		runModeIsProd:  true ,
		customEmojis: {"codeberg":":codeberg:","git":":git:","gitea":":gitea:","github":":github:","gitlab":":gitlab:","gogs":":gogs:"},
		useServiceWorker:  false ,
		csrfToken: '2a80waZwBSC2sF97y-ubGsOaaqg6MTY4MDQwODAyODU4NDYyNTYwMA',
		pageData: {},
		requireTribute:  null ,
		notificationSettings: {"EventSourceUpdateTime":10000,"MaxTimeout":60000,"MinTimeout":10000,"TimeoutStep":10000}, 
		enableTimeTracking:  true ,
		
		mermaidMaxSourceCharacters:  5000 ,
		
		i18n: {
			copy_success: 'Copied!',
			copy_error: 'Copy failed',
			error_occurred: 'An error occurred',
			network_error: 'Network error',
		},
	};
	
	window.config.pageData = window.config.pageData || {};
</script>

	<noscript>
		<style>
			.dropdown:hover > .menu { display: block; }
			.ui.secondary.menu .dropdown.item > .menu { margin-top: 0; }
		</style>
	</noscript>

	<meta property="og:title" content="Trustie: Git with trustie">
	<meta property="og:type" content="website">
	<meta property="og:image" content="/assets/img/logo.png">
	<meta property="og:url" content="https://gitlink.org.cn/">
	<meta property="og:description" content="Gitea (Git with a cup of tea) is a painless self-hosted Git service written in Go">

<meta property="og:site_name" content="Trustie: Git with trustie">

	<link rel="stylesheet" href="/assets/css/theme-auto.css?v=development">


</head>
<body>
	

	<div class="full height">
		<noscript>This website works better with JavaScript.</noscript>

		

		
			<div class="ui top secondary stackable main menu following bar light no-vertical-tabs">
				<div class="ui container" id="navbar">
	
	
	<div class="item brand" style="justify-content: space-between;">
		<a href="/" aria-label="Home">
			<img width="30" height="30" src="/assets/img/logo.svg" alt="Logo" aria-hidden="true">
		</a>
		
		<div class="ui basic icon button mobile-only" id="navbar-expand-toggle">
			<i class="sidebar icon"></i>
		</div>
	</div>

	
		<a class="item " href="/explore/repos">Explore</a>
	

	

	


	
		<a class="item" target="_blank" rel="noopener noreferrer" href="https://docs.gitea.io">Help</a>
		<div class="right stackable menu">
			
			<a class="item active" rel="nofollow" href="/user/login">
				<svg viewBox="0 0 16 16" class="svg octicon-sign-in" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M2 2.75C2 1.784 2.784 1 3.75 1h2.5a.75.75 0 0 1 0 1.5h-2.5a.25.25 0 0 0-.25.25v10.5c0 .138.112.25.25.25h2.5a.75.75 0 0 1 0 1.5h-2.5A1.75 1.75 0 0 1 2 13.25V2.75zm6.56 4.5 1.97-1.97a.75.75 0 1 0-1.06-1.06L6.22 7.47a.75.75 0 0 0 0 1.06l3.25 3.25a.75.75 0 1 0 1.06-1.06L8.56 8.75h5.69a.75.75 0 0 0 0-1.5H8.56z"/></svg> Sign In
			</a>
		</div>
	
</div>

			</div>
		



<div class="page-content user signin">
	
<div class="ui secondary pointing tabular top attached borderless menu new-menu navbar">
	<div class="new-menu-inner">
		<a class="active item" rel="nofollow" href="/user/login">
			Sign In
		</a>
		
		<a class=" item" rel="nofollow" href="/user/login/openid">
			<svg viewBox="0 0 448 448" class="svg fontawesome-openid" width="16" height="16" aria-hidden="true"><path d="M271.5 0v384l-68 32C88.5 405.75 0 344.5 0 270.25c0-71.5 82.5-131 191.75-144.25v43c-71.5 12.5-124 53-124 101.25 0 51 58.5 93.25 135.75 103v-340zm167.25 145.5L448 243l-131.25-28.5 36.75-20.75c-19.5-11.5-43.5-20-70-24.75v-43c46.25 5.5 87.75 19.5 120.25 39.25z"/></svg>
			&nbsp;OpenID
		</a>
		
		
	</div>
</div>


	<div class="ui middle very relaxed page grid">
		<div class="ui container column fluid">
					
		




		
		<h4 class="ui top attached header center">
			
				Sign In
			
		</h4>
		<div class="ui attached segment">
			<form class="ui form" action="/user/login" method="post">
			<input type="hidden" name="_csrf" value="2a80waZwBSC2sF97y-ubGsOaaqg6MTY4MDQwODAyODU4NDYyNTYwMA">
			<div class="required inline field ">
				<label for="user_name">Username or Email Address</label>
				<input id="user_name" type="text" name="user_name" value="" autofocus required>
			</div>
			
			<div class="required inline field ">
				<label for="password">Password</label>
				<input id="password" name="password" type="password" value="" autocomplete="current-password" required>
			</div>
			
			
			<div class="inline field">
				<label></label>
				<div class="ui checkbox">
					<label>Remember this Device</label>
					<input name="remember" type="checkbox">
				</div>
			</div>
			

			<div class="inline field">
				<label></label>
				<button class="ui green button">
					
						Sign In
					
				</button>
				<a href="/user/forgot_password">Forgot password?</a>
			</div>

			

			
			</form>
		</div>

		</div>
	</div>
</div>


	

	</div>

	

	<footer>
	<div class="ui container">
		<div class="ui left">
			<a target="_blank" rel="noopener noreferrer" href="https://gitea.io">Powered by Gitea</a>
			
				Version:
				
					development
				
			
			
				Page: <strong>2ms</strong>
				Template: <strong>0ms</strong>
			
		</div>
		<div class="ui right links">
			
			<div class="ui language bottom floating slide up dropdown link item">
				<svg viewBox="0 0 16 16" class="svg octicon-globe" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M1.543 7.25h2.733c.144-2.074.866-3.756 1.58-4.948.12-.197.237-.381.353-.552a6.506 6.506 0 0 0-4.666 5.5zm2.733 1.5H1.543a6.506 6.506 0 0 0 4.666 5.5 11.13 11.13 0 0 1-.352-.552c-.715-1.192-1.437-2.874-1.581-4.948zm1.504 0h4.44a9.637 9.637 0 0 1-1.363 4.177c-.306.51-.612.919-.857 1.215a9.978 9.978 0 0 1-.857-1.215A9.637 9.637 0 0 1 5.78 8.75zm4.44-1.5H5.78a9.637 9.637 0 0 1 1.363-4.177c.306-.51.612-.919.857-1.215.245.296.55.705.857 1.215A9.638 9.638 0 0 1 10.22 7.25zm1.504 1.5c-.144 2.074-.866 3.756-1.58 4.948-.12.197-.237.381-.353.552a6.506 6.506 0 0 0 4.666-5.5h-2.733zm2.733-1.5h-2.733c-.144-2.074-.866-3.756-1.58-4.948a11.738 11.738 0 0 0-.353-.552 6.506 6.506 0 0 1 4.666 5.5zM8 0a8 8 0 1 0 0 16A8 8 0 0 0 8 0z"/></svg>
				<div class="text">English</div>
				<div class="menu language-menu">
					
						<a lang="id-ID" data-url="/?lang=id-ID" class="item ">Bahasa Indonesia</a>
					
						<a lang="de-DE" data-url="/?lang=de-DE" class="item ">Deutsch</a>
					
						<a lang="en-US" data-url="/?lang=en-US" class="item active selected">English</a>
					
						<a lang="es-ES" data-url="/?lang=es-ES" class="item ">Español</a>
					
						<a lang="fr-FR" data-url="/?lang=fr-FR" class="item ">Français</a>
					
						<a lang="it-IT" data-url="/?lang=it-IT" class="item ">Italiano</a>
					
						<a lang="lv-LV" data-url="/?lang=lv-LV" class="item ">Latviešu</a>
					
						<a lang="hu-HU" data-url="/?lang=hu-HU" class="item ">Magyar nyelv</a>
					
						<a lang="nl-NL" data-url="/?lang=nl-NL" class="item ">Nederlands</a>
					
						<a lang="pl-PL" data-url="/?lang=pl-PL" class="item ">Polski</a>
					
						<a lang="pt-PT" data-url="/?lang=pt-PT" class="item ">Português de Portugal</a>
					
						<a lang="pt-BR" data-url="/?lang=pt-BR" class="item ">Português do Brasil</a>
					
						<a lang="fi-FI" data-url="/?lang=fi-FI" class="item ">Suomi</a>
					
						<a lang="sv-SE" data-url="/?lang=sv-SE" class="item ">Svenska</a>
					
						<a lang="tr-TR" data-url="/?lang=tr-TR" class="item ">Türkçe</a>
					
						<a lang="cs-CZ" data-url="/?lang=cs-CZ" class="item ">Čeština</a>
					
						<a lang="el-GR" data-url="/?lang=el-GR" class="item ">Ελληνικά</a>
					
						<a lang="bg-BG" data-url="/?lang=bg-BG" class="item ">Български</a>
					
						<a lang="ru-RU" data-url="/?lang=ru-RU" class="item ">Русский</a>
					
						<a lang="uk-UA" data-url="/?lang=uk-UA" class="item ">Українська</a>
					
						<a lang="fa-IR" data-url="/?lang=fa-IR" class="item ">فارسی</a>
					
						<a lang="ml-IN" data-url="/?lang=ml-IN" class="item ">മലയാളം</a>
					
						<a lang="ja-JP" data-url="/?lang=ja-JP" class="item ">日本語</a>
					
						<a lang="zh-CN" data-url="/?lang=zh-CN" class="item ">简体中文</a>
					
						<a lang="zh-TW" data-url="/?lang=zh-TW" class="item ">繁體中文（台灣）</a>
					
						<a lang="zh-HK" data-url="/?lang=zh-HK" class="item ">繁體中文（香港）</a>
					
						<a lang="ko-KR" data-url="/?lang=ko-KR" class="item ">한국어</a>
					
				</div>
			</div>
			<a href="/assets/js/licenses.txt">Licenses</a>
			<a href="/api/swagger">API</a>
			
		</div>
	</div>
</footer>




	<script src="/assets/js/index.js?v=development" onerror="alert('Failed to load asset files from ' + this.src + ', please make sure the asset files can be accessed and the ROOT_URL setting in app.ini is correct.')"></script>

</body>
</html>

