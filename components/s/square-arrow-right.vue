<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc33d-p1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zc33d-p1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrow-right" /></template>
