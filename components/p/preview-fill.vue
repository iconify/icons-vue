<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2ik1qbwi.css';
import '../../css/d/ddoe6f8-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2ik1qbwi"/><path class="ddoe6f8-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:preview-fill" /></template>
