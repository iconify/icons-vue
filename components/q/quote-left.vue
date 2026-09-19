<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afeyf_wkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afeyf_wkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:quote-left" /></template>
