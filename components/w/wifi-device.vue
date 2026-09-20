<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcrr3jb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wifi-device" /></template>
<style>
.tcrr3jb1s {
  fill: currentColor;
  d: path("M7.308 20h9.365q1.38 0 2.354-.963q.973-.964.973-2.345V7.327q0-1.38-.973-2.354Q18.054 4 16.673 4H7.308q-1.381 0-2.344.973Q4 5.946 4 7.327v9.365q0 1.362.973 2.335T7.308 20m.044-8.783l-.74-.663q.973-1.16 2.404-1.741T12 8.23q1.54 0 2.966.582t2.398 1.74l-.741.664q-.856-.988-2.068-1.487T12 9.23t-2.564.49q-1.223.49-2.084 1.497m2.62 2.677l-.733-.694q.534-.584 1.252-.902q.719-.317 1.515-.317t1.518.317t1.257.902l-.727.694q-.408-.432-.94-.673q-.531-.24-1.114-.24t-1.111.24q-.53.24-.918.673m1.509 2.626q-.21-.21-.21-.52t.21-.52t.52-.21t.52.21t.21.52t-.21.52t-.52.21t-.52-.21");
}

</style>
