<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0ai68bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="h0ai68bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wifi-router" /></template>
