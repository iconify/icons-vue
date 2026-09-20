<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cai2cxbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cai2cxbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:rotate-right-solid" /></template>
