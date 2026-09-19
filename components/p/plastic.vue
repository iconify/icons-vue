<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aes_y_brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aes_y_brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:plastic" /></template>
