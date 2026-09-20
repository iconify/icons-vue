<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hns9v-b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hns9v-b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:presentation2-filled" /></template>
