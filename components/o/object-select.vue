<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki54wzl-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ki54wzl-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:object-select" /></template>
