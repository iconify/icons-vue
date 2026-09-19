<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlo8iz2zo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlo8iz2zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:umbrella-alt-filled" /></template>
