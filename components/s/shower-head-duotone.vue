<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/df5km-bgn.css';
import '../../css/p/pishzubsf.css';
import '../../css/i/ix1b_41hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="df5km-bgn"/><path class="pishzubsf"/><path class="ix1b_41hr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shower-head-duotone" /></template>
