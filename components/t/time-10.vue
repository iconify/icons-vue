<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrhkwmnpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="vrhkwmnpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:time-10" /></template>
