<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb4jysoyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb4jysoyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:prohibited-2-line" /></template>
