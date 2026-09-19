<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvgnh32ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dvgnh32ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:radiation-solid" /></template>
