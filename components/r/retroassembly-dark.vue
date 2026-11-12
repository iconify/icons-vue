<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biy6uzn1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="biy6uzn1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:retroassembly-dark" /></template>
