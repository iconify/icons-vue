<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t55u-kbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t55u-kbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:xls-outline" /></template>
