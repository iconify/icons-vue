<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmynu6bpt.css';
import '../../css/c/c8_g7taxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="lmynu6bpt"/><path clip-rule="evenodd" class="c8_g7taxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:water-drop-1" /></template>
