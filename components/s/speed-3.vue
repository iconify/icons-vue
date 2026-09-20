<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd1zshyki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-3" /></template>
<style>
.rd1zshyki {
  fill: currentColor;
  d: path("M12.729 15.492q.619-.298.823-.936t-.18-1.19q-1.316-1.902-2.602-3.768T8.16 5.854q.59 2.225 1.206 4.41q.617 2.184 1.284 4.378q.192.652.822.898q.63.245 1.257-.048M5.106 19q-.281 0-.513-.112t-.391-.338q-.604-1.084-.906-2.253q-.302-1.168-.302-2.408q.006-1.827.735-3.451t1.96-2.83T8.546 5.7T12 5q1.864 0 3.503.71q1.64.711 2.858 1.93t1.929 2.857Q21 12.137 21 14q0 1.196-.302 2.337q-.302 1.14-.894 2.136q-.14.264-.385.395T18.9 19z");
}

</style>
