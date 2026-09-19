<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coyl4abfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="coyl4abfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pascal" /></template>
