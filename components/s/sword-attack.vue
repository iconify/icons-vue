<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp-s39uks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp-s39uks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:sword-attack" /></template>
