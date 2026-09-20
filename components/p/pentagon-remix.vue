<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw_gh8mfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zw_gh8mfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pentagon-remix" /></template>
