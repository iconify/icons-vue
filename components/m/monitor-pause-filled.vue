<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2ty35bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2ty35bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-pause-filled" /></template>
