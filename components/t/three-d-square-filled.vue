<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km51robcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km51robcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:three-d-square-filled" /></template>
