<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="n3dj_jz-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shield-arrow-right-28-filled" /></template>
<style>
.n3dj_jz-i {
  fill: currentColor;
  d: path("M13.56 2.142a.75.75 0 0 1 .878 0c.643.464 2.088 1.312 3.897 2.041c1.81.73 3.922 1.317 5.913 1.317a.75.75 0 0 1 .75.75v7.752q0 .243-.015.485a7.5 7.5 0 0 0-9.855 11.247a8 8 0 0 1-1 .242l-.13.022l-.128-.022c-2.205-.385-4.9-1.917-7.033-4.024C4.703 19.843 3 17.029 3 14.002V6.25a.75.75 0 0 1 .75-.75c1.991 0 4.103-.587 5.914-1.317c1.808-.73 3.253-1.577 3.896-2.04M27 20.5a6.5 6.5 0 1 0-13 0a6.5 6.5 0 0 0 13 0m-11 0a.5.5 0 0 1 .5-.5h6.793l-2.147-2.146a.5.5 0 0 1 .708-.708l3 3a.5.5 0 0 1 .146.351v.006a.5.5 0 0 1-.146.35l-3 3a.5.5 0 0 1-.708-.707L23.293 21H16.5a.5.5 0 0 1-.5-.5");
}

</style>
