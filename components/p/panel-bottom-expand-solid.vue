<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz9u0m0if.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz9u0m0if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:panel-bottom-expand-solid" /></template>
