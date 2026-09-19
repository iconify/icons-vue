<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni5y2_bcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ni5y2_bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:timelapse" /></template>
