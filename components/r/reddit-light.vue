<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgqwleb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kgqwleb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reddit-light" /></template>
