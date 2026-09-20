<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m96ctz9ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m96ctz9ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:text-align-right-solid" /></template>
