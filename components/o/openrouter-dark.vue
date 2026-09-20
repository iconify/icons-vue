<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d50imbb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d50imbb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openrouter-dark" /></template>
