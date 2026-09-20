<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6fvp9b0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6fvp9b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:message-text2-filled" /></template>
