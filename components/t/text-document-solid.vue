<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1_ig-50q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="w1_ig-50q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:text-document-solid" /></template>
