<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq6wnx2rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq6wnx2rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:package-plus-solid" /></template>
