<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb8e72srw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb8e72srw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:uber-symbol" /></template>
