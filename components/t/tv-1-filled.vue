<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvh306brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvh306brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tv-1-filled" /></template>
