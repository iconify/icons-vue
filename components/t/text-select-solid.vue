<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk34cc_mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk34cc_mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:text-select-solid" /></template>
