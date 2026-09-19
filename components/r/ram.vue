<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlcufkbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="mlcufkbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:ram" /></template>
