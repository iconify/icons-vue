<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj746xb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj746xb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:umbrella-gloss" /></template>
