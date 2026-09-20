<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz6fvbc1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jz6fvbc1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:toyota-dark" /></template>
