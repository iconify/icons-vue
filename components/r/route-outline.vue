<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx9tb8boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dx9tb8boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:route-outline" /></template>
