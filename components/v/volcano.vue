<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdldj9b0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdldj9b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:volcano" /></template>
