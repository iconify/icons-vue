<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymxp5z6_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymxp5z6_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:threads" /></template>
