<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en3ahzbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en3ahzbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rectangle-vertical-line" /></template>
