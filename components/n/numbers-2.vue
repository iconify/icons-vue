<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in1b-kb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in1b-kb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-2" /></template>
