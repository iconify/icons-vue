<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0x0msb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="a0x0msb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:moleculer-wordmark" /></template>
