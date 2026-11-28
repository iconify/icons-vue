<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz1yogb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz1yogb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:type-solid" /></template>
