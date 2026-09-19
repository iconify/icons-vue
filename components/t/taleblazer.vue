<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="gi7-35bac"/><path class="fqrt0ffjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:taleblazer" /></template>
<style>
.fqrt0ffjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.148 30.448L39.505 42.5l2.871-2.625l-12.849-11.532M15.14 13.602c.95 1.111 1.184 1.735 2.05 2.991c.136.197-2.589 2.912-4.332.602c-1.323-1.754 1.873-4.072 2.281-3.593m1.463-.729s1.168 1.868 1.91 2.96c.105.155 1.583-.891 2.99-1.344s3.537-2.338 2.974-3.707c-.84-1.88-3.218-2.162-4.753-1.336c-2.06 1.48-3.247 2.996-3.121 3.427m2.064 14.947c-.89-1.16-1.452-1.518-2.502-2.626c-.164-.174-3.385 1.93-1.486 4.113c1.441 1.658 4.371-.987 3.988-1.486m1.016-1.279s-1.586-1.53-2.501-2.483c-.13-.135 1.2-1.364 1.935-2.647s3.02-2.975 4.243-2.14c1.664 1.212 1.448 3.597.322 4.926c-1.876 1.708-3.604 2.556-4 2.344");
}

.gi7-35bac {
  cx: 19.324px;
  cy: 19.201px;
  r: 13.7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
