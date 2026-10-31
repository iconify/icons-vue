<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc-xamhui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc-xamhui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toolbox-fill-round" /></template>
