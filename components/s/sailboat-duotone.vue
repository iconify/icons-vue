<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/odr5n16ys.css';
import '../../css/f/fuqcm9bty.css';
import '../../css/g/gnp_skboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="odr5n16ys"/><path class="fuqcm9bty"/><path class="gnp_skboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sailboat-duotone" /></template>
