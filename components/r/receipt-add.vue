<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt35nhx6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rt35nhx6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:receipt-add" /></template>
