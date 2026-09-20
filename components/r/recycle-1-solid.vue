<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvoy9l1zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tvoy9l1zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:recycle-1-solid" /></template>
