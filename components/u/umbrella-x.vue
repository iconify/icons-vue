<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w400v9b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w400v9b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:umbrella-x" /></template>
