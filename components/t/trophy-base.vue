<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6ajgtnjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i6ajgtnjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:trophy-base" /></template>
