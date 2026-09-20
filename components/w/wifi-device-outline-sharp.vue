<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnxjslgtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wifi-device-outline-sharp" /></template>
<style>
.rnxjslgtz {
  fill: currentColor;
  d: path("M5 5h14v14H5zM4 4v16h16V4zm3.352 7.217l-.74-.663q.973-1.16 2.404-1.741T12 8.23q1.54 0 2.966.582t2.398 1.74l-.741.664q-.856-.988-2.068-1.487T12 9.23t-2.564.49q-1.223.49-2.084 1.497m2.62 2.677l-.733-.694q.534-.584 1.252-.902q.719-.317 1.515-.317t1.518.317t1.257.902l-.727.694q-.408-.432-.94-.673q-.531-.24-1.114-.24t-1.111.24q-.53.24-.918.673m1.509 2.626q-.21-.21-.21-.52t.21-.52t.52-.21t.52.21t.21.52t-.21.52t-.52.21t-.52-.21M12 12");
}

</style>
