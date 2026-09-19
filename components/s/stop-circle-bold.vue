<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4m2zw2yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z4m2zw2yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:stop-circle-bold" /></template>
