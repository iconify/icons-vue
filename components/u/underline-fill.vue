<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwt8cbcha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwt8cbcha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:underline-fill" /></template>
