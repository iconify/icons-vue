<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjmj-wusv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kjmj-wusv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mouse-1-bold" /></template>
