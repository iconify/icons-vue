<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fee3yq8ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fee3yq8ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-close-corner-round" /></template>
