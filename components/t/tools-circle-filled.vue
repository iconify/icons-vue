<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjx7gcb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjx7gcb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tools-circle-filled" /></template>
