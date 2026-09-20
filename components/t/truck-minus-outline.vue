<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1u83iczg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1u83iczg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:truck-minus-outline" /></template>
