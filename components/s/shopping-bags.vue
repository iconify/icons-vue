<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/e/e6cpddcyw.css';
import '../../css/r/ry3rr2hev.css';
import '../../css/e/eu2bi-boo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="e6cpddcyw"/><path class="ry3rr2hev"/><path class="eu2bi-boo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shopping-bags" /></template>
