<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/x/x-_5ilohg.css';
import '../../css/o/of52wgbuj.css';
import '../../css/s/sd8cfcjbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x-_5ilohg"/><path class="of52wgbuj"/><path class="sd8cfcjbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-divide-sharp" /></template>
