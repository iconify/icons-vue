<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz8krcb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xz8krcb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:phone-arrow-right" /></template>
