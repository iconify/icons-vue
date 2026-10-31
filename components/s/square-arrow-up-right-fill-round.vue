<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn8pkrgel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn8pkrgel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-up-right-fill-round" /></template>
