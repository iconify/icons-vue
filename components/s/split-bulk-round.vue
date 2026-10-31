<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5n2a1blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5n2a1blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:split-bulk-round" /></template>
