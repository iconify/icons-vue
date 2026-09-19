<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr0w__b2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rr0w__b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-lastfm" /></template>
