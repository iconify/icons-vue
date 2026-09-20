<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4f0s_zex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p4f0s_zex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mortar-pestle-solid" /></template>
