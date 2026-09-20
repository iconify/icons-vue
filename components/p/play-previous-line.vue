<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei8_h1b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei8_h1b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:play-previous-line" /></template>
