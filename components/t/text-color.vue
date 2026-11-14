<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl8yd4beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:text-color" /></template>
<style>
.yl8yd4beu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m5.335 14.653l6-11.5q.034-.065.081-.123q.046-.058.102-.105q.057-.047.122-.083q.065-.035.135-.057q.071-.023.144-.031t.147-.001q.074.006.145.027t.136.055q.209.109.318.318l6 11.5q.034.066.055.136t.027.145q.007.074-.001.147t-.031.144t-.057.135q-.036.065-.083.122t-.105.102q-.058.047-.123.081q-.132.069-.281.082t-.291-.032t-.257-.14t-.183-.228L15.328 11.5H8.672l-2.007 3.847q-.069.132-.183.228q-.115.096-.257.14t-.291.032t-.281-.082q-.065-.034-.123-.081q-.058-.046-.105-.102q-.047-.057-.083-.122q-.035-.065-.057-.135q-.023-.071-.031-.144t-.001-.147t.027-.145t.055-.136M14.545 10L12 5.121L9.455 10zM3.336 18.336q.586-.586 1.414-.586h14.5q2 0 2 2q0 .828-.586 1.414t-1.414.586H4.75q-.828 0-1.414-.586T2.75 19.75t.586-1.414");
}

</style>
