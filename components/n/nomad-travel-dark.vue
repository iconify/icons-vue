<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff6aicbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ff6aicbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nomad-travel-dark" /></template>
