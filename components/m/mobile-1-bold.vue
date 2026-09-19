<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-mgk2ajy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="y-mgk2ajy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mobile-1-bold" /></template>
