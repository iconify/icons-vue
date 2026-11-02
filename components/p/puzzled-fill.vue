<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anbbfhm_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anbbfhm_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:puzzled-fill" /></template>
