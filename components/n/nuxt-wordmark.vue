<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5z6y8bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="g5z6y8bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:nuxt-wordmark" /></template>
