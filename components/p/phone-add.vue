<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0xqrdqrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="a0xqrdqrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:phone-add" /></template>
