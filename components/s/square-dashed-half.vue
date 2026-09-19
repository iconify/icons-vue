<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox8tpsb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b ox8tpsb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:square-dashed-half" /></template>
