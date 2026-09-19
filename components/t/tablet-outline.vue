<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hco61nbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hco61nbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:tablet-outline" /></template>
