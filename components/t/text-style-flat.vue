<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbvbyfttg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sbvbyfttg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:text-style-flat" /></template>
