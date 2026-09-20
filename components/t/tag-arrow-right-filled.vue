<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju98jybvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ju98jybvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tag-arrow-right-filled" /></template>
