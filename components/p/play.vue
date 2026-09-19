<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2h63xbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="j2h63xbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:play" /></template>
