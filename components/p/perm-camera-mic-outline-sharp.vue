<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oacv9lb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:perm-camera-mic-outline-sharp" /></template>
<style>
.oacv9lb9r {
  fill: currentColor;
  d: path("M9.5 20H3V6h4.573l1.85-2h5.154l1.85 2H21v14h-6.5v-1H20V7h-4.011l-1.845-2H9.856L8.012 7H4v12h5.5zm2 0h1v-3.408q1.939-.234 3.22-1.637Q17 13.552 17 11.615h-1q0 1.593-1.156 2.797Q13.69 15.615 12 15.615t-2.844-1.203Q8 13.208 8 11.616H7q0 1.936 1.28 3.339q1.282 1.403 3.22 1.637zm1.374-7.51q.357-.357.357-.875v-4q0-.517-.357-.874T12 6.385t-.874.356t-.357.875v4q0 .517.357.874t.874.356t.874-.356M4 19h16z");
}

</style>
