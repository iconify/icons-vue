<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuqks-fnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuqks-fnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:planet-filled" /></template>
