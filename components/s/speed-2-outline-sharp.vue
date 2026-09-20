<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr18y0ulh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-2-outline-sharp" /></template>
<style>
.gr18y0ulh {
  fill: currentColor;
  d: path("M13.208 15.175q.476-.477.436-1.144t-.586-1.064q-1.822-1.338-3.716-2.673T5.63 7.662q1.292 1.825 2.646 3.716t2.675 3.697q.404.552 1.083.574t1.175-.474M4.458 19q-.702-1.287-1.086-2.454q-.383-1.167-.378-2.657q.006-1.112.29-2.168q.283-1.055.808-2.044l.681.862q-.406.8-.592 1.643T3.994 13.9q0 1.1.269 2.138T5.107 18H18.9q.525-.9.813-1.912T20 14q0-3.325-2.337-5.663T12 6q-.925 0-1.803.206q-.878.205-1.697.605l-.9-.642Q8.608 5.6 9.72 5.3T12 5q1.872 0 3.507.71q1.635.711 2.853 1.93t1.93 2.853T21 14q0 1.466-.397 2.599T19.503 19zm7.67-4.854");
}

</style>
