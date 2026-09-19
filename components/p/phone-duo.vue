<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec4nlpgpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ec4nlpgpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:phone-duo" /></template>
