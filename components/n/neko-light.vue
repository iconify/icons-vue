<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl4ov37_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cl4ov37_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:neko-light" /></template>
