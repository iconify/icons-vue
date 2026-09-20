<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfx2fdc4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gfx2fdc4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:peppermint" /></template>
