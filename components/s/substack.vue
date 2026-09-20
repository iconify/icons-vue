<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px37m5f4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px37m5f4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:substack" /></template>
