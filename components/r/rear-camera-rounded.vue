<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jay5yl1kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rear-camera-rounded" /></template>
<style>
.jay5yl1kt {
  fill: currentColor;
  d: path("M16.77 7.52q.21-.21.21-.52t-.21-.52t-.52-.21t-.52.21t-.21.52t.21.52t.52.21t.52-.21M12.5 19h6.885q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T19.385 5H12.5zm-7.884 1q-.691 0-1.153-.462T3 18.384v-5.076q0-.349.23-.578t.578-.23h3.604l-1.766 1.766q-.14.14-.13.334q.009.194.15.335q.14.14.344.14t.344-.14l2.369-2.37q.243-.242.243-.565t-.243-.565L6.335 9.046q-.14-.14-.335-.14t-.334.14q-.141.14-.141.345q0 .203.14.344L7.413 11.5H3.808q-.348 0-.578-.23T3 10.692V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616v12.769q0 .69-.463 1.153T19.385 20z");
}

</style>
