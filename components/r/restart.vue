<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxk_-ubon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxk_-ubon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:restart" /></template>
