<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iul73ibuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":740,"height":840};
const content = `<path class="iul73ibuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:tag" /></template>
