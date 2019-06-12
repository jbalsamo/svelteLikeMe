<script>
  export let altText;
  export let iurl;
</script>

<style>
	logo {
	  border: 2px;
	  padding: 8px 12px;
	  border-radius: 2px;
	}
</style>

<logo>
  <img alt={altText} src={iurl} />
</logo>
