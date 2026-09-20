<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-ye_xbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-ye_xbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:play-box-lock" /></template>
