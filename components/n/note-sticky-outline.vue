<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6qqgkbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="t6qqgkbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:note-sticky-outline" /></template>
