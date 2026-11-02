<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i79vfgbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i79vfgbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shower-gel-fill" /></template>
