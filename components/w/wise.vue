<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx0ijld1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx0ijld1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wise" /></template>
