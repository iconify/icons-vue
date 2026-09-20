<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgo5f8b1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgo5f8b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-lines" /></template>
