<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krpodeq0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="krpodeq0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:move-horizontally" /></template>
