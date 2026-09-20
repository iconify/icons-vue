<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t57l3zbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t57l3zbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zotero-dark" /></template>
