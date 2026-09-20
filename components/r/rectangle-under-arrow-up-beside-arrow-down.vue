<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k81q3hz4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k81q3hz4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rectangle-under-arrow-up-beside-arrow-down" /></template>
