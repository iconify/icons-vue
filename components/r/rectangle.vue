<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqwng4bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="fqwng4bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:rectangle" /></template>
