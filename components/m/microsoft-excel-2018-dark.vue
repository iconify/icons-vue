<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2lkowdni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y2lkowdni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-excel-2018-dark" /></template>
