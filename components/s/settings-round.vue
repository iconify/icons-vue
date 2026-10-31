<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csb-3693b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csb-3693b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:settings-round" /></template>
