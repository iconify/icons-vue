<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qikjditnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="qikjditnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:street-light-1" /></template>
