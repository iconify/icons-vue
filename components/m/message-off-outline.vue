<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo_c-qbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo_c-qbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-off-outline" /></template>
