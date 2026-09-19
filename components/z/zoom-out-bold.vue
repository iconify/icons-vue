<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n416p013c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="n416p013c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:zoom-out-bold" /></template>
