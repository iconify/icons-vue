<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d15wwo3kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d15wwo3kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openbooks" /></template>
