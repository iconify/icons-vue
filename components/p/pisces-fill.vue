<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgu141ten.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgu141ten"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pisces-fill" /></template>
