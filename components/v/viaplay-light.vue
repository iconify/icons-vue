<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvs72d4fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uvs72d4fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:viaplay-light" /></template>
