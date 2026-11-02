<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk935jbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk935jbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:utensils-line" /></template>
