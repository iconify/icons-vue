<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhdghibwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xhdghibwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:sax" /></template>
