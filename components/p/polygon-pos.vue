<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2u1e0bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2u1e0bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:polygon-pos" /></template>
