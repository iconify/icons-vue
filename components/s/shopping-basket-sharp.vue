<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd289rbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shopping-basket-sharp" /></template>
<style>
.xd289rbue {
  fill: currentColor;
  d: path("m4.833 20l-2.85-10H7.75l4.264-6.429L16.239 10h5.778L19.13 20zm7.868-4.299Q13 15.402 13 15t-.299-.701T12 14t-.701.299T11 15t.299.701T12 16t.701-.299M8.964 10h6.067l-3.037-4.623z");
}

</style>
