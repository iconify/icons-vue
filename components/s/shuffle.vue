<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlciivbhx.css';
import '../../css/q/qhg6yeb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlciivbhx"/><path class="qhg6yeb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shuffle" /></template>
