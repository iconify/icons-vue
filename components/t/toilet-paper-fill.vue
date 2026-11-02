<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkwozubwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkwozubwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toilet-paper-fill" /></template>
