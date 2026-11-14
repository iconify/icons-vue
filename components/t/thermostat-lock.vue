<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq1t40rud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:thermostat-lock" /></template>
<style>
.xq1t40rud {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.625 1.75h4.75q2.848 0 4.861 2.014t2.014 4.861v4.37q-.971-.745-2.25-.745q-1.791 0-2.726.855q.476-.954.476-2.105q0-1.968-1.391-3.359T11 6.25T7.641 7.641T6.25 11t1.391 3.359T11 15.75t3.359-1.391q.107-.108.206-.219q-.265.65-.307 1.524Q13 16.578 13 18.75v1q0 .256.03.5H8.625q-2.848 0-4.861-2.014T1.75 13.375v-4.75q0-2.848 2.014-4.861T8.625 1.75m12.393 15.232q-.243-.242-.518-.404V16q0-1.036-.732-1.768T18 13.5q-2.5 0-2.5 2.5v.464q-1.25.518-1.25 2.286v1q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768M19 16.25h-2V16q0-1 1-1q.414 0 .707.293T19 16zm-3.25 2.5q0-1 1-1h2.5q1 0 1 1v1q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707zM17 19h.345q-.17.123-.345.234z");
}

</style>
