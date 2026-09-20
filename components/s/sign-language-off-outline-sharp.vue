<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqgv9q-vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sign-language-off-outline-sharp" /></template>
<style>
.vqgv9q-vb {
  fill: currentColor;
  d: path("m7.51 18.04l-5.666-1.05l.196-.988l5.75 1.07zm.911-3.246l-6.469-1.748l.294-.944l6.45 1.729zm5.454-5.671l-4.05-5.827l.798-.586l4.056 5.838zm4.017 5.92l-.717-.706l1.629-1.11q.188-.133.334-.318q.145-.186.214-.444L20.55 7.77l-2.604 2.848l-3.477-8.342l.914-.41l2.886 6.899l2.11-2.341l1.388.748l-1.451 5.587q-.112.423-.354.739q-.243.317-.571.534zm-3.867-.993L4.812 9.298l.502-.885l6.377 3.302zM2.667 21.221l.118-.988L11.53 21q.86.094 1.556-.392q.696-.487.934-1.327l.881-2.939L2.092 3.508L2.8 2.8l18.4 18.4l-.708.708l-4.83-4.806l-.677 2.46q-.343 1.175-1.338 1.869T11.433 22zm14.508-6.884");
}

</style>
