<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzpp4026n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pzpp4026n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:stop-outline" /></template>
