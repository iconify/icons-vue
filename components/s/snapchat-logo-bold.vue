<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvu0c9bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvu0c9bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:snapchat-logo-bold" /></template>
