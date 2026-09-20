<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbqlomwxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tbqlomwxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pencil" /></template>
