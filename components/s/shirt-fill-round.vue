<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-d-hbipu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-d-hbipu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shirt-fill-round" /></template>
