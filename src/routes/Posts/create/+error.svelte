<script lang="ts">
    import { page } from '$app/stores';
</script>

<h1>Yikes</h1>

<p>There was an error creating your post. Please try again.</p>

<pre>
    {JSON.stringify($page, null, 2)}
</pre>