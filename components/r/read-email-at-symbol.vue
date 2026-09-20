<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsgau738b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsgau738b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:read-email-at-symbol" /></template>
