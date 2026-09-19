<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riu0g0nxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="riu0g0nxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-kebab-horizontal-fill" /></template>
