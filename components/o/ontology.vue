<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7grrr7pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ontology" /></template>
<style>
.s7grrr7pv {
  fill: var(--svg-color--49a3ff, #49a3ff);
  d: path("M3 10.891V3.387l14.85 15.321c-.306.259-4.014 3.3-8.424 1.946c-3.843-1.18-6.561-5.18-6.417-9.772zm17.973 2.25L21 20.589L6.105 5.314c.306-.267 4.014-3.319 8.415-1.973c3.852 1.162 6.597 5.18 6.453 9.79z");
}

</style>
