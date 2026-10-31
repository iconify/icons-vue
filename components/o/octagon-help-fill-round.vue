<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2ok6dbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2ok6dbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-help-fill-round" /></template>
