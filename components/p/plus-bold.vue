<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py_xqg_-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="py_xqg_-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:plus-bold" /></template>
