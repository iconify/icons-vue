<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imkvacbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="imkvacbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pullapprove" /></template>
