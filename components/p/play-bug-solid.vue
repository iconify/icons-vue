<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffybyabpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffybyabpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:play-bug-solid" /></template>
