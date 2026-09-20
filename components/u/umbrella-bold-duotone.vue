<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/epu_tj-1c.css';
import '../../css/g/ghvq8sbip.css';
import '../../css/t/t2b8qbc3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="epu_tj-1c"/><path class="ghvq8sbip"/><path class="t2b8qbc3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:umbrella-bold-duotone" /></template>
