<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8ds3ac-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l8ds3ac-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:polaroid-outline" /></template>
