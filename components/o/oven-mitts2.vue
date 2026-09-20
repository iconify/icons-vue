<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw_8thb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vw_8thb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:oven-mitts2" /></template>
