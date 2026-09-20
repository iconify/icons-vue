<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm2btmm-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm2btmm-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:shapes-solid" /></template>
