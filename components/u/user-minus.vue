<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxq8u4x7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxq8u4x7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:user-minus" /></template>
