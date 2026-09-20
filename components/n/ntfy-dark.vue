<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph-134bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ph-134bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ntfy-dark" /></template>
