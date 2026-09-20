<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ltz3hlb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shield-28-filled" /></template>
<style>
.ltz3hlb4a {
  fill: currentColor;
  d: path("M13.56 2.142a.75.75 0 0 1 .878 0c.643.464 2.088 1.312 3.897 2.041c1.81.73 3.922 1.317 5.913 1.317a.75.75 0 0 1 .75.75v7.752c0 3.027-1.703 5.841-3.838 7.95c-2.133 2.107-4.827 3.64-7.033 4.024l-.128.022l-.129-.022c-2.205-.385-4.9-1.917-7.033-4.024C4.703 19.843 3 17.029 3 14.002V6.25a.75.75 0 0 1 .75-.75c1.991 0 4.103-.587 5.914-1.317c1.808-.73 3.253-1.577 3.896-2.04");
}

</style>
