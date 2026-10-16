<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lml3v6bum.css';
import '../../css/w/wgzcd4bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":57.6,"height":19.5};
const content = `<path class="lml3v6bum"/><path class="wgzcd4bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:saleor" /></template>
