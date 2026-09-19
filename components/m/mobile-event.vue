<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c70yz9b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c70yz9b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mobile-event" /></template>
