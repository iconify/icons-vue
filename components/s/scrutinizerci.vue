<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hokl__b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hokl__b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:scrutinizerci" /></template>
