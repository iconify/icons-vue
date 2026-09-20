<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_0o3568j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v_0o3568j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:trash" /></template>
