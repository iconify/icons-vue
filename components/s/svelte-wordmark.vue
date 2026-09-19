<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv8p9kb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="iv8p9kb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:svelte-wordmark" /></template>
