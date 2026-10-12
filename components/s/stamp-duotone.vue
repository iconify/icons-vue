<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e5vg7rbbw.css';
import '../../css/e/e1ce3wbbz.css';
import '../../css/n/ntr3o-yjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e5vg7rbbw"/><path class="e1ce3wbbz"/><path class="ntr3o-yjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:stamp-duotone" /></template>
