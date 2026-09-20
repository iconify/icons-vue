<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa461_q4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa461_q4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:video-question-mark-fill" /></template>
