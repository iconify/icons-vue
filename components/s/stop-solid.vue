<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofp7wzg4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ofp7wzg4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:stop-solid" /></template>
