<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/totghng7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="totghng7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:wrap-arc-upper-flat" /></template>
