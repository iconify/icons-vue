<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4h2p03zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="e4h2p03zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:user" /></template>
