<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxoghot-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zxoghot-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mouse-2-outline" /></template>
