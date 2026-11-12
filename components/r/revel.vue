<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p12ryjbsv.css';
import '../../css/k/k5azw7b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p12ryjbsv"/><path class="k5azw7b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:revel" /></template>
