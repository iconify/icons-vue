<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm_k9ga6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zm_k9ga6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:pungo" /></template>
