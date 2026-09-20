<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5le61biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5le61biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-round-square-fill" /></template>
