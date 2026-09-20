<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2l3_-b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h2l3_-b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:star-badge-solid" /></template>
