<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seh-xkbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="seh-xkbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:qnt" /></template>
