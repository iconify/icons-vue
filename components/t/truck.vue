<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnqiikm4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="wnqiikm4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:truck" /></template>
