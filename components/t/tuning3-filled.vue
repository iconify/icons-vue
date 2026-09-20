<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akj5c-bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akj5c-bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tuning3-filled" /></template>
