<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjh9_9bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjh9_9bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reload-duocolor-round" /></template>
