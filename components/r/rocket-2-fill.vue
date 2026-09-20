<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vscn6xb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vscn6xb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rocket-2-fill" /></template>
