<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/v/vhj6biypl.css';
import '../../css/l/l9gqw4bde.css';
import '../../css/t/t-fa8-bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vhj6biypl"/><path class="l9gqw4bde"/><path class="t-fa8-bok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shirt-sparkles-sharp-duotone" /></template>
