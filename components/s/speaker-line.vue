<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fucl7wbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fucl7wbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:speaker-line" /></template>
