<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-5-fgb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w-5-fgb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nixos-dark" /></template>
