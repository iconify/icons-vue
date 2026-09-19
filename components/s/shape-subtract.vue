<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mabaapu1g.css';
import '../../css/h/hhh60ljkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mabaapu1g"/><path class="hhh60ljkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-subtract" /></template>
