<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf-_vsrid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uf-_vsrid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xibo-dark" /></template>
