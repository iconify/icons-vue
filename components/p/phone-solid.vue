<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh4ts9bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yh4ts9bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:phone-solid" /></template>
