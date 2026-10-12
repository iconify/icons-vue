<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sk78vjtmq.css';
import '../../css/y/yjlljib5h.css';
import '../../css/k/ks1ls910s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sk78vjtmq"/><path class="yjlljib5h"/><path class="ks1ls910s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-x-duotone" /></template>
