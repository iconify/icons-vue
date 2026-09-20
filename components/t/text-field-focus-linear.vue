<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gayebnb-o.css';
import '../../css/r/rmc1u9j4i.css';
import '../../css/o/om4lnzbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gayebnb-o"/><path class="rmc1u9j4i"/><path class="om4lnzbpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-field-focus-linear" /></template>
