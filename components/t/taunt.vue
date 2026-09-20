<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulbuldqcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:taunt" /></template>
<style>
.ulbuldqcv {
  fill: currentColor;
  d: path("M5.412 14.514q-.427.228-.91.099q-.483-.13-.736-.532q-.31-.514-.103-1.077t.778-.762l8.463-2.915l.477.948zm.415 5.755v-4.886l8.898-4.677l-.425-.856l4.796-2.408l.496.974l-6.765 5.103v6.75zm-.263-10.14Q4.692 9.258 4.692 8t.872-2.129T7.692 5t2.13.871t.87 2.129t-.87 2.129t-2.13.871t-2.128-.871");
}

</style>
