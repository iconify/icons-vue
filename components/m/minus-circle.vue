<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaqkji9ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iaqkji9ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:minus-circle" /></template>
