<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhu35gblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yhu35gblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mbin-light" /></template>
