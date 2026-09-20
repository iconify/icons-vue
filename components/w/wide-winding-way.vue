<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8xrxen5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r8xrxen5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wide-winding-way" /></template>
