<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkcntybyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkcntybyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:settings-4-line" /></template>
