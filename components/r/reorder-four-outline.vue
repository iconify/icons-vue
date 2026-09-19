<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v910tplip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v910tplip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:reorder-four-outline" /></template>
