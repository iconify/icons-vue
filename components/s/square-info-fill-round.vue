<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9iix5bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9iix5bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-info-fill-round" /></template>
