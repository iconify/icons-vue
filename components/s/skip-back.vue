<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4govwbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4govwbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:skip-back" /></template>
