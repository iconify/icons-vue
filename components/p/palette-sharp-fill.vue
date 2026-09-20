<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/estk-xb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="estk-xb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:palette-sharp-fill" /></template>
