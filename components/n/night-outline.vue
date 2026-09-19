<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phb2crpck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="phb2crpck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:night-outline" /></template>
