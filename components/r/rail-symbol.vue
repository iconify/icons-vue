<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd9u0ph8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd9u0ph8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:rail-symbol" /></template>
