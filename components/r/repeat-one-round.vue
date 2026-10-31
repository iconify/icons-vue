<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojsrp14pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojsrp14pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:repeat-one-round" /></template>
