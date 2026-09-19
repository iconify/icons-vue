<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5yeiybgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5yeiybgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:upload-circle-filled" /></template>
