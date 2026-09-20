<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6ru7ho_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-3-rounded" /></template>
<style>
.u6ru7ho_f {
  fill: currentColor;
  d: path("M12.729 15.492q.596-.292.814-.93t-.172-1.196q-.927-1.364-1.876-2.698T9.608 7.97q-.218-.292-.534-.143t-.216.484q.438 1.594.878 3.173q.441 1.579.914 3.16q.192.663.835.902q.644.24 1.244-.053M5.106 19q-.281 0-.513-.112t-.391-.338q-.604-1.084-.906-2.253q-.302-1.168-.302-2.408q.006-1.827.735-3.451t1.96-2.83T8.546 5.7T12 5q1.864 0 3.503.71q1.64.711 2.858 1.93t1.929 2.857Q21 12.137 21 14q0 1.196-.302 2.337q-.302 1.14-.894 2.136q-.14.264-.385.395T18.9 19z");
}

</style>
