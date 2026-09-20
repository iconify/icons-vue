<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/ro541xb1r.css';
import '../../css/c/cfifa2ueo.css';
import '../../css/h/hub4u5b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ro541xb1r"/><path class="cfifa2ueo"/><path clip-rule="evenodd" class="hub4u5b3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:phone-calling-bold-duotone" /></template>
