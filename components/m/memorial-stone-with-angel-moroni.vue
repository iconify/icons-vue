<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo7o1fc6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xo7o1fc6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone-with-angel-moroni" /></template>
