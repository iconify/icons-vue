<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdt7u2b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdt7u2b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-warning-round" /></template>
