<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd8dcdbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd8dcdbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pizza-round" /></template>
