<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nppc4ldyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nppc4ldyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:refresh-cw-filled" /></template>
