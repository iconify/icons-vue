<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8ci34jwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8ci34jwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:open-ai" /></template>
