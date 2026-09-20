<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8hf1gbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8hf1gbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:trophy-solid" /></template>
