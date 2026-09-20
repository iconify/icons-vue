<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty5zirbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty5zirbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:plug2-filled" /></template>
