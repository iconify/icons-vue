<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5gekdb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f5gekdb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:raindrop-io-light" /></template>
