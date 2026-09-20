<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqwmo6byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqwmo6byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:thought-line" /></template>
