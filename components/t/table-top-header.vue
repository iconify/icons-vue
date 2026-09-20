<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc5zuv2sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="uc5zuv2sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:table-top-header" /></template>
