<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyhj_obng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gyhj_obng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-arrow-left" /></template>
