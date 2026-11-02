<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egumsho2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egumsho2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-circle-check-line" /></template>
