<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcst-z.css';
import '../../css/a/a0m25c.css';
import '../../css/c/c2m0_y.css';
import '../../css/v/vwcgvo.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-34.css';
import '../../css/s/so-from-16.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcst-z"/><path class="a0m25c c2m0_y"/><path class="a0m25c vwcgvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:star-right-half-alt-filled" /></template>
