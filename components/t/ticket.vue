<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8jnmpbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="i8jnmpbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ticket" /></template>
