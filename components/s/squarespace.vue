<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbynunb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qbynunb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:squarespace" /></template>
