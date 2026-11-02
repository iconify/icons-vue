<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjf-5bbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjf-5bbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ufo-2-line" /></template>
