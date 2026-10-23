<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9sjz1bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9sjz1bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tally-4" /></template>
