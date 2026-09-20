<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz7wrdbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz7wrdbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sunglasses" /></template>
