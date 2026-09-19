<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgf-f2bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lgf-f2bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:watchman" /></template>
