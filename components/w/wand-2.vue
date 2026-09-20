<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k07w6ccsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k07w6ccsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:wand-2" /></template>
