<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyyqn4wxr.css';
import '../../css/y/yuqpybceb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="vyyqn4wxr"/><path class="yuqpybceb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-trim-filled" /></template>
