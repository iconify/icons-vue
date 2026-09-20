<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3tkxm7_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="p3tkxm7_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:surfing" /></template>
