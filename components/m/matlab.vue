<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t54jjfbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t54jjfbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:matlab" /></template>
