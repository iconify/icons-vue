<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7ctxokii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7ctxokii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sorting-1-9" /></template>
