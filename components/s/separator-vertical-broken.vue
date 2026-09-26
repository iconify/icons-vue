<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/l678ypbwk.css';
import '../../css/m/mwz2inb5v.css';
import '../../css/x/x1f4lc3zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l678ypbwk"/><path class="mwz2inb5v"/><path class="x1f4lc3zb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:separator-vertical-broken" /></template>
