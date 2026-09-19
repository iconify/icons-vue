<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jig-cofsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jig-cofsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:mg" /></template>
