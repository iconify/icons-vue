<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qenv9tbnd.css';
import '../../css/t/tj44tabky.css';
import '../../css/w/wk6uvki7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qenv9tbnd"/><path class="tj44tabky"/><path class="wk6uvki7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sofa-duotone" /></template>
