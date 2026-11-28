<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5kl3zbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5kl3zbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:superscript-solid" /></template>
