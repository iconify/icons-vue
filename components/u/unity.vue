<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goem8ebtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="goem8ebtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:unity" /></template>
