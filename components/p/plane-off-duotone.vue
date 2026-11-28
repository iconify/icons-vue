<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb-w71_su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zb-w71_su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:plane-off-duotone" /></template>
