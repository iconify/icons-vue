<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktzywfrhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ktzywfrhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:play-filled" /></template>
