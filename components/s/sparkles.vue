<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hew9mwplw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hew9mwplw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:sparkles" /></template>
