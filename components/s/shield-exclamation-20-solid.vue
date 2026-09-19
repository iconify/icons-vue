<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwtz2ebrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rwtz2ebrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:shield-exclamation-20-solid" /></template>
