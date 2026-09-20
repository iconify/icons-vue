<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on3e_0i0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-sharp" /></template>
<style>
.on3e_0i0v {
  fill: currentColor;
  d: path("M4.98 21V3H19v18zm3.712-4.711h6.577V7.73H8.692zm1-1v-4.673h4.577v4.673zm2.303-9.231q.267 0 .472-.203q.206-.203.206-.493q0-.268-.202-.469t-.471-.2q-.292 0-.482.2q-.191.201-.191.469q0 .29.189.493q.19.203.479.203m-.006 13.288q.273 0 .469-.203t.196-.493q0-.267-.201-.468q-.2-.201-.469-.201q-.29 0-.483.2q-.193.201-.193.47q0 .29.193.492q.193.203.488.203");
}

</style>
