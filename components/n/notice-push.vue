<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcfp9s-0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGt6KFdcQE" class="wcfp9s-0x"/></defs><use href="#SVGt6KFdcQE"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:notice-push" /></template>
