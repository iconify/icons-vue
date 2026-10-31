<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_joi3_le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_joi3_le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-bulk-round" /></template>
