<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-5f2htjo.css';
import '../../css/v/vbsmhsbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-5f2htjo"/><path class="vbsmhsbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifier-bold" /></template>
