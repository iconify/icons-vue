<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgxtv_kog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hgxtv_kog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:speaker-0-16" /></template>
