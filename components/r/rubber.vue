<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb2so-xcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-2.5};
const content = `<path class="wb2so-xcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:rubber" /></template>
