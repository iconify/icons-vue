<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dff48eqvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dff48eqvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:warning-multiple-filled" /></template>
