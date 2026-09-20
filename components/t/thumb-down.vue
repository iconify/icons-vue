<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ookz8by-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ookz8by-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:thumb-down" /></template>
