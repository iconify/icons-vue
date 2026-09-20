<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lynb7gb5s.css';
import '../../css/e/ei9w4bc3h.css';
import '../../css/t/tbgu7rb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="bi12bsetm"><path class="lynb7gb5s"/><path class="ei9w4bc3h"/><path class="tbgu7rb4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:tv-mode" /></template>
