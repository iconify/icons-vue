<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvyj2k6nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zvyj2k6nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:placemark" /></template>
