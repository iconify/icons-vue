<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw-szkbrd.css';
import '../../css/f/f96gcgbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw-szkbrd"/><path clip-rule="evenodd" class="f96gcgbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:transmission-bold-duotone" /></template>
