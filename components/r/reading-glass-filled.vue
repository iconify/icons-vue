<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddwiuu_lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b ddwiuu_lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:reading-glass-filled" /></template>
