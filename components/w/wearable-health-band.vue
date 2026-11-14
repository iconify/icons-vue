<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u37vktb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wearable-health-band" /></template>
<style>
.u37vktb9y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 7V3.5q0-1.75 1.75-1.75h5q1.75 0 1.75 1.75V7q0 .134-.046.26q-.047.125-.134.227q.255.206.496.447Q18.25 9.618 18.25 12t-1.684 4.066q-.241.241-.496.447q.087.102.134.227q.046.126.046.26v3.5q0 1.75-1.75 1.75h-5q-1.75 0-1.75-1.75V17q0-.134.046-.26q.047-.125.134-.227q-.255-.206-.496-.447Q5.75 14.382 5.75 12t1.684-4.066q.241-.241.496-.447q-.087-.102-.134-.227Q7.75 7.134 7.75 7m7-3.5q0-.25-.25-.25h-5q-.25 0-.25.25v3.189q1.034-.439 2.25-.439h1q1.216 0 2.25.439zm-3.166 11.874q.092.062.199.094q.106.032.217.032t.217-.032t.199-.094Q15.5 13.318 15.5 11.25q0-2.5-2.5-2.5q-.569 0-1 .318q-.431-.318-1-.318q-2.5 0-2.5 2.5q0 2.068 3.084 4.124M9.25 17.311V20.5q0 .25.25.25h5q.25 0 .25-.25v-3.189q-1.034.439-2.25.439h-1q-1.216 0-2.25-.439");
}

</style>
