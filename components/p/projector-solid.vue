<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgvez0b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kgvez0b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:projector-solid" /></template>
