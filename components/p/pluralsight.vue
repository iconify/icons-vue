<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypzmo_bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ypzmo_bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:pluralsight" /></template>
