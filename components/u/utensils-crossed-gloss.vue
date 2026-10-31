<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6lj_ebwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6lj_ebwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:utensils-crossed-gloss" /></template>
