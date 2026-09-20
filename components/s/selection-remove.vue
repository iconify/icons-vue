<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl0-88b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl0-88b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:selection-remove" /></template>
