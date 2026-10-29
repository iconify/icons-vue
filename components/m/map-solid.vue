<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9ji8acvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9ji8acvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:map-solid" /></template>
