<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5z1rjb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="i5z1rjb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:phone-outline" /></template>
