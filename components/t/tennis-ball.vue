<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsg9ci29x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsg9ci29x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tennis-ball" /></template>
