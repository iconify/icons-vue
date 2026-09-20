<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbngs4vpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="gbngs4vpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pointer-left" /></template>
