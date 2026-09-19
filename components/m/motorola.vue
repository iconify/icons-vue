<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le4acc5tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="le4acc5tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:motorola" /></template>
