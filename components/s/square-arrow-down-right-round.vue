<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iajds0bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iajds0bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-down-right-round" /></template>
