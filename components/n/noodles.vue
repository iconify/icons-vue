<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl2z6zbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl2z6zbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:noodles" /></template>
