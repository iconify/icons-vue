<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0n02obus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="u0n02obus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-secret" /></template>
