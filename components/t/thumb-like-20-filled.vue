<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="raytv3bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:thumb-like-20-filled" /></template>
<style>
.raytv3bzn {
  fill: currentColor;
  d: path("M9.805 3.058c.19-.789 1.072-1.297 1.859-.95q.026.008.098.038a2.9 2.9 0 0 1 .842.581c.462.463.896 1.213.895 2.354c0 .642-.133 1.536-.257 2.242c-.045.25-.092.482-.13.678h.886a3 3 0 0 1 2.947 3.561l-.624 3.277a4.5 4.5 0 0 1-5.612 3.498l-5.552-1.525a2.5 2.5 0 0 1-1.793-1.94l-.319-1.657c-.246-1.282.543-2.447 1.603-2.995c3.436-1.774 4.718-5.343 5.157-7.162");
}

</style>
