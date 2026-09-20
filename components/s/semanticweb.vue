<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-mluac3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-mluac3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:semanticweb" /></template>
