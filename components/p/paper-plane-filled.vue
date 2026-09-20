<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh7bcpbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh7bcpbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:paper-plane-filled" /></template>
