<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sat67kbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="sat67kbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:table-col-before" /></template>
