<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj3rtbc3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gj3rtbc3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:removarr-light" /></template>
