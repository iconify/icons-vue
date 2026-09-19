<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sylp2urel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sylp2urel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:mobile" /></template>
