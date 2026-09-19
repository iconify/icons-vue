<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sno9zvbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":895};
const content = `<path class="sno9zvbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:wallet" /></template>
