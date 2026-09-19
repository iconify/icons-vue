<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vddvmpaot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vddvmpaot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:pencil-outline" /></template>
