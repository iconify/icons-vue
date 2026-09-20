<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9g4i8bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z9g4i8bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:marreta-dark" /></template>
