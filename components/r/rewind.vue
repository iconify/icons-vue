<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9krgsina.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="w9krgsina"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:rewind" /></template>
