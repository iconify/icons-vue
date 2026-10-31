<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blzdssbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blzdssbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-duocolor-round" /></template>
