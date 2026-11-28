<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9_w5wtle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9_w5wtle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-split-bottom-right-solid" /></template>
