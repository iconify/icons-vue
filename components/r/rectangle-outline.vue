<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwauig-7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fwauig-7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:rectangle-outline" /></template>
