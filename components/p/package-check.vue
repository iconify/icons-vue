<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl9bqpbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl9bqpbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-check" /></template>
