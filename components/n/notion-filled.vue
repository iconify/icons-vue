<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oydwh62tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oydwh62tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:notion-filled" /></template>
