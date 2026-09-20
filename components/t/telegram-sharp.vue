<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf7pgp-ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf7pgp-ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:telegram-sharp" /></template>
