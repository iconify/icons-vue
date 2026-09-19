<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifjm3fbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="ifjm3fbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:texture" /></template>
