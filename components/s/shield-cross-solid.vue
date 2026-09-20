<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysk_kx6wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ysk_kx6wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:shield-cross-solid" /></template>
