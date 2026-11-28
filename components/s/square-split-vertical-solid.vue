<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtx8mq7hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtx8mq7hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-split-vertical-solid" /></template>
