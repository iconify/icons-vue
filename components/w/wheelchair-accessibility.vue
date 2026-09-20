<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0ak4m-da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0ak4m-da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wheelchair-accessibility" /></template>
