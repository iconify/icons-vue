<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q09b9zepi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q09b9zepi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:venus-round" /></template>
