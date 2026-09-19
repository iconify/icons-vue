<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzx2lebap.css';
import '../../css/m/mrexazbtc.css';
import '../../css/e/e-qw-wqmo.css';
import '../../css/o/o9wti8bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="xzx2lebap"/><path class="mrexazbtc"/><path class="e-qw-wqmo"/><path clip-rule="evenodd" class="o9wti8bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ohmyzsh" /></template>
