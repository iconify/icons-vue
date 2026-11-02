<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfgz6bbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfgz6bbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-question-line" /></template>
