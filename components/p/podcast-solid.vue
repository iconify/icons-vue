<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r57bgcc3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r57bgcc3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:podcast-solid" /></template>
