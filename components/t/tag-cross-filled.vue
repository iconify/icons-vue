<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwyfkgblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwyfkgblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tag-cross-filled" /></template>
