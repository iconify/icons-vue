<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpd_lfb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cpd_lfb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:vk" /></template>
