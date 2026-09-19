<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxdi6zbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="lxdi6zbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:note-pad-bold" /></template>
