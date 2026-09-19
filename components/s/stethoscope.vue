<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7dcahbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":19,"height":24};
const content = `<path class="d7dcahbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:stethoscope" /></template>
