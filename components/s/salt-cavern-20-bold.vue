<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf341pb1x.css';
import '../../css/z/z4ddoubly.css';
import '../../css/x/xshgi_b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yf341pb1x"/><path class="z4ddoubly"/><path class="xshgi_b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:salt-cavern-20-bold" /></template>
