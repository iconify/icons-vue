<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsne3db-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vsne3db-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:superscript" /></template>
