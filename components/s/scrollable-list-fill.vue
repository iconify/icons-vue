<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3e1-4bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3e1-4bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scrollable-list-fill" /></template>
