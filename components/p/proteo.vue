<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4cnmn_xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVG2Ib8ObKe" class="h4cnmn_xu"/></defs><use href="#SVG2Ib8ObKe"/><use href="#SVG2Ib8ObKe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:proteo" /></template>
