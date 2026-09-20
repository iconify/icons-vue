<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym11dybwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ym11dybwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shield-check-solid" /></template>
