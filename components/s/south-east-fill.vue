<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn1x1w7ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xn1x1w7ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:south-east-fill" /></template>
