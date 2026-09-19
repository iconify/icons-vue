<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyupctqcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":9.12,"height":16};
const content = `<path class="fyupctqcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:pause" /></template>
