<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw6_mhbkb.css';
import '../../css/w/wbu9xubvi.css';
import '../../css/z/zfrriw87y.css';
import '../../css/n/nxw8z6bfd.css';
import '../../css/x/xhnsdjblr.css';
import '../../css/s/sud4f5b2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cw6_mhbkb"/><path class="wbu9xubvi"/><path class="zfrriw87y"/><path class="nxw8z6bfd"/><path class="xhnsdjblr"/><path class="sud4f5b2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-turbine-offshore-spinning-20-bold" /></template>
