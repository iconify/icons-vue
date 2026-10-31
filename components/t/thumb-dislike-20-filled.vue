<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mbo-lg6ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:thumb-dislike-20-filled" /></template>
<style>
.mbo-lg6ic {
  fill: currentColor;
  d: path("M9.803 16.94c.19.79 1.072 1.298 1.858.952l.001-.001l.098-.038q.084-.035.216-.107c.172-.096.4-.248.625-.474c.463-.463.897-1.213.896-2.354c0-.642-.133-1.536-.258-2.242c-.044-.25-.09-.482-.13-.678h.886a3 3 0 0 0 2.947-3.561l-.624-3.277a4.5 4.5 0 0 0-5.611-3.498L5.154 3.187a2.5 2.5 0 0 0-1.793 1.939l-.318 1.658c-.246 1.282.543 2.447 1.602 2.994c3.437 1.775 4.718 5.343 5.158 7.162");
}

</style>
