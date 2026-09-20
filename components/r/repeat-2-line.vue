<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgi8beuri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgi8beuri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:repeat-2-line" /></template>
