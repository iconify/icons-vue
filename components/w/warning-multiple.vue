<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w80zo3biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w80zo3biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:warning-multiple" /></template>
