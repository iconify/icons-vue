<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osmryt6ri.css';
import '../../css/n/nzqrsacsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osmryt6ri"/><path class="nzqrsacsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:markup-line" /></template>
