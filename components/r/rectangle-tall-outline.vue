<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cho2ybc2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cho2ybc2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rectangle-tall-outline" /></template>
