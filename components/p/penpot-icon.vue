<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":339};
const content = `<path class="aurnuce7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:penpot-icon" /></template>
<style>
.aurnuce7i {
  d: path("M153.71 50.078L189.268 0l35.558 50.078v28.279l30.948 14.721l.227-.107v184.681l-120.628 56.99L128 338.12l-7.371-3.48L0 277.653V92.972l.279.13l30.94-14.716V50.078L66.774 0l35.393 49.848l25.67-36.16l25.874 36.44zM14.742 116.24v152.073l105.888 50.021V166.262zm226.516 0l-105.885 50.021v152.073l105.885-50.02zm-89.575-44.334h-18.914v79.283l18.914-8.937zm-28.675 0h-19.012v70.191l19.012 8.983zM90.62 58.218H71.703v68.626l18.917 8.935zm93.816 0h-19.01v77.54l19.01-8.98zm-122.494 0H42.93v55.034l19.01 8.982zm151.168 0h-18.915v63.948l18.915-8.936zM31.219 92.97l-16.735 6.842l16.735 7.907zm193.602-.025v14.75l16.739-7.906zM134.128 42.78l-12.74.226l-13.59 19.14h40.082zM73.064 29.09l-12.74.227l-13.592 19.14h40.085zm122.491 0l-12.741.227l-13.59 19.14h40.087z");
}

</style>
