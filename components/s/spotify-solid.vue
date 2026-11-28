<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu0s4ebai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu0s4ebai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:spotify-solid" /></template>
