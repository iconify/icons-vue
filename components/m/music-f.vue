<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2-3o1b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-1.5};
const content = `<path class="v2-3o1b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:music-f" /></template>
