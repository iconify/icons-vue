<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1628quib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a1628quib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:nine-outline" /></template>
