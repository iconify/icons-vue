<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qao93n-ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qao93n-ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tree-deciduous" /></template>
