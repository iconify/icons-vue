<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwuxu7bdj.css';
import '../../css/z/zkrs_kb_e.css';
import '../../css/w/wp-cwqm9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<defs><linearGradient id="SVGUFVlnbzA" x1="199.997" x2="296.665" y1="214.302" y2="307.573" gradientTransform="translate(-200 -213)" gradientUnits="userSpaceOnUse"><stop offset="0" class="bwuxu7bdj"/><stop offset="1" class="zkrs_kb_e"/></linearGradient></defs><path fill="url(#SVGUFVlnbzA)" class="wp-cwqm9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vscodium" /></template>
