<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urxscpbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-display-off" /></template>
<style>
.urxscpbjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.03 3.082Q7.448 3 7.875 3h8.25q.107 0 .215.005q.107.006.214.016t.213.026t.212.037t.209.047t.207.057t.204.068t.2.077t.197.087t.191.097t.187.105q.092.056.182.115q.089.06.175.124t.169.132t.163.14t.156.148t.148.156t.14.163t.132.169t.124.175t.115.182q.055.092.105.187q.051.094.097.191q.046.098.087.197t.077.2t.068.204q.031.103.057.207t.047.209q.021.106.037.212t.026.213t.016.214t.005.215v6.25q0 .608-.166 1.193t-.485 1.103M14.019 18H7.875q-.107 0-.215-.005q-.107-.006-.214-.016t-.213-.026t-.212-.037t-.209-.047q-.104-.026-.207-.057t-.204-.068q-.101-.036-.2-.077t-.197-.087t-.191-.097q-.095-.05-.187-.105q-.092-.056-.182-.115q-.089-.06-.175-.124t-.169-.132t-.163-.14t-.156-.148t-.148-.156t-.14-.163t-.132-.169t-.124-.175t-.115-.182t-.105-.187q-.051-.094-.097-.191q-.046-.098-.087-.197t-.077-.2t-.068-.204t-.057-.207t-.047-.209t-.037-.212t-.026-.213t-.016-.214t-.005-.215V7.466M12 18v3m-3.5 0h7M3.5 3.5l17 17");
}

</style>
