<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnr0c4bhl.css';
import '../../css/p/p3pc--btm.css';
import '../../css/h/h5196ibum.css';
import '../../css/o/og2qqobav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGe8GOYbwn" x1="29.49" x2="169.71" y1="29.48" y2="169.7" gradientUnits="userSpaceOnUse"><stop offset="0" class="bnr0c4bhl"/><stop offset="1" class="p3pc--btm"/></linearGradient><linearGradient id="SVGJueaZf4v" x1="28.05" x2="168.27" y1="30.92" y2="171.14" gradientTransform="translate(.006)scale(.63997)" href="#SVGe8GOYbwn"/><linearGradient id="SVGjKyrtbBu" x1="29.49" x2="169.71" y1="29.48" y2="169.7" gradientTransform="translate(.006)scale(.63997)" gradientUnits="userSpaceOnUse" href="#SVGe8GOYbwn"/></defs><path fill="url(#SVGjKyrtbBu)" class="h5196ibum"/><path fill="url(#SVGJueaZf4v)" class="og2qqobav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:svgo" /></template>
