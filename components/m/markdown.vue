<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk9qbrbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qk9qbrbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:markdown" /></template>
