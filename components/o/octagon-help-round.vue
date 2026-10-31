<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-3k8hbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-3k8hbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-help-round" /></template>
