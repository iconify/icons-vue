<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sruzenvtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sruzenvtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:rearrange-fill-20" /></template>
