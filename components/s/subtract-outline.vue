<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxmvmcvjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kxmvmcvjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:subtract-outline" /></template>
