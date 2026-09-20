<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0oydobxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<rect class="i0oydobxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:stop-filled" /></template>
