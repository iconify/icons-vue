<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoazjybag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":220,"height":220};
const content = `<path class="xoazjybag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:milanote-light" /></template>
