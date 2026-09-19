<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxtlc09iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxtlc09iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:question-mark" /></template>
