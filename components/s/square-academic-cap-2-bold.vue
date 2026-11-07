<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glh9vkb1x.css';
import '../../css/u/u1vdsvbke.css';
import '../../css/k/kp08yd09g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glh9vkb1x"/><path class="u1vdsvbke"/><path class="kp08yd09g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-academic-cap-2-bold" /></template>
