<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdyoa5b9x.css';
import '../../css/o/oy550fbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdyoa5b9x"/><path class="oy550fbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:notes-checklist-flip-bold" /></template>
