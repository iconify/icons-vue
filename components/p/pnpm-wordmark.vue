<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha-tytpvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ha-tytpvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:pnpm-wordmark" /></template>
