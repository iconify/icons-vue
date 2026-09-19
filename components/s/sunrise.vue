<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adb_bacik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1472};
const content = `<path class="adb_bacik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:sunrise" /></template>
