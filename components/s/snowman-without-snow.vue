<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6w6x0bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="o6w6x0bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:snowman-without-snow" /></template>
