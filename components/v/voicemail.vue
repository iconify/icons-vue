<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6-h_fbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6-h_fbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:voicemail" /></template>
