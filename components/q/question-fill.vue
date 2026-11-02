<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-j6szbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-j6szbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:question-fill" /></template>
