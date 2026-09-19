<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bug2scxnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="bug2scxnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:rewind" /></template>
