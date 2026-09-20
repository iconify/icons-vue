<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzwd_xb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pzwd_xb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:navigation-arrow-north" /></template>
