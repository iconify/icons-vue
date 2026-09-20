<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx7nwqb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-outline-sharp" /></template>
<style>
.jx7nwqb7g {
  fill: currentColor;
  d: path("M4.98 21V3H19v18zm1-1H18V4H5.98zm2.712-3.712h6.577V7.731H8.692zm1-1v-4.672h4.577v4.673zm2.303-8.73q.267 0 .472-.203q.206-.203.206-.493q0-.268-.202-.469t-.471-.2q-.292 0-.482.2q-.191.201-.191.469q0 .29.189.493q.19.203.479.203m0 12.269q.267 0 .472-.193q.206-.193.206-.489q0-.272-.202-.468T12 17.481q-.292 0-.482.2q-.191.201-.191.47q0 .29.189.483q.19.193.479.193M12 12");
}

</style>
