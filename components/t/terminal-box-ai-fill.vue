<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb2h4eb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb2h4eb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:terminal-box-ai-fill" /></template>
