<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdk78rbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="wdk78rbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:visa" /></template>
