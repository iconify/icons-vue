<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh97csgkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dh97csgkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-fall-minimalistic-2-outline" /></template>
