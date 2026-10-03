<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9j6e4_4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9j6e4_4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:text-align-justify-center" /></template>
