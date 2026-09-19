<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0jte5bwq.css';
import '../../css/u/u738m78mn.css';
import '../../css/e/e8odnlcxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f0jte5bwq"/><path class="u738m78mn"/><path class="e8odnlcxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tool-kit" /></template>
