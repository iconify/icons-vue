<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czhtycbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czhtycbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:video-slash-solid" /></template>
