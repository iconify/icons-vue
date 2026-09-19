<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr941acet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr941acet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-plus-duotone" /></template>
