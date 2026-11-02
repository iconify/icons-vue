<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y72i1swld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y72i1swld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wifi-off-fill" /></template>
