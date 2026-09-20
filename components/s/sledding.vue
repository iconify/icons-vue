<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io_ltac6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="io_ltac6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:sledding" /></template>
