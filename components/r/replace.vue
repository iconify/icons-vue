<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg74q_5-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg74q_5-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:replace" /></template>
