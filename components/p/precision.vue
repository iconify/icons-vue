<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oarmztb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oarmztb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:precision" /></template>
