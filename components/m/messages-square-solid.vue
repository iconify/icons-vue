<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgey5gbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgey5gbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:messages-square-solid" /></template>
