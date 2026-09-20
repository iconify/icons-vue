<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc45uznfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-alt-off-outline-rounded" /></template>
<style>
.kc45uznfp {
  fill: currentColor;
  d: path("M12.043 18.765q-.235-.236-.235-.573v-4.957L3.094 4.52q-.146-.146-.155-.347t.155-.366t.357-.166t.357.166l16.384 16.384q.147.147.156.345t-.156.363t-.356.166t-.357-.166l-6.056-6.05v3.342q0 .337-.236.573q-.235.235-.571.235q-.337 0-.573-.236m6.15-3.72q-.307-.005-.557-.217t-.251-.59v-8.43q0-.336.235-.571q.236-.236.572-.236t.573.236q.235.235.235.572v8.429q0 .403-.251.608t-.557.2m-10.812.19q.235.236.235.573v2.384q0 .337-.235.573q-.236.235-.572.235t-.573-.236Q6 18.53 6 18.193v-2.384q0-.337.235-.572q.236-.236.573-.236t.572.236");
}

</style>
