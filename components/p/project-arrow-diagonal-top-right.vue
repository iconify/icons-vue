<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9xohdbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="q9xohdbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:project-arrow-diagonal-top-right" /></template>
