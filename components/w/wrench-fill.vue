<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcx_-ubej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcx_-ubej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:wrench-fill" /></template>
