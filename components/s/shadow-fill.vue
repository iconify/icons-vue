<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8z_edcic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8z_edcic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shadow-fill" /></template>
