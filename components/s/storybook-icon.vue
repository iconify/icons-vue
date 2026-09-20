<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":319};
const content = `<defs><path id="SVGCjwircEr" class="a66j17bbi"/></defs><mask id="SVGd4Xo1w9i" class="n1mjunbsu"><use href="#SVGCjwircEr"/></mask><use href="#SVGCjwircEr" class="heeii1f4x"/><path mask="url(#SVGd4Xo1w9i)" class="nflhq8v3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:storybook-icon" /></template>
<style>
.a66j17bbi {
  d: path("M9.872 293.324L.012 30.574C-.315 21.895 6.338 14.54 15.005 14L238.494.032c8.822-.552 16.42 6.153 16.972 14.975q.03.498.031.998v286.314c0 8.839-7.165 16.004-16.004 16.004q-.36 0-.718-.016l-213.627-9.595c-8.32-.373-14.963-7.065-15.276-15.388");
}

.heeii1f4x {
  fill: var(--svg-color--ff4785, #ff4785);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.nflhq8v3y {
  fill: var(--svg-color--fff, #fff);
  d: path("m188.665 39.127l1.527-36.716L220.884 0l1.322 37.863a2.387 2.387 0 0 1-3.864 1.96l-11.835-9.325l-14.013 10.63a2.387 2.387 0 0 1-3.829-2.001m-39.251 80.853c0 6.227 41.942 3.243 47.572-1.131c0-42.402-22.752-64.684-64.415-64.684c-41.662 0-65.005 22.628-65.005 56.57c0 59.117 79.78 60.249 79.78 92.494c0 9.052-4.433 14.426-14.184 14.426c-12.705 0-17.729-6.49-17.138-28.552c0-4.786-48.458-6.278-49.936 0c-3.762 53.466 29.548 68.887 67.665 68.887c36.935 0 65.892-19.687 65.892-55.326c0-63.36-80.961-61.663-80.961-93.06c0-12.728 9.455-14.425 15.07-14.425c5.909 0 16.546 1.042 15.66 24.801");
}

</style>
