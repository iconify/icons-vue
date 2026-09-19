<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v50ep0b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v50ep0b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:tenzir-wordmark" /></template>
