<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1b5yub_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j1b5yub_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:paved-road-24px" /></template>
