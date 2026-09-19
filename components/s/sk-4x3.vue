<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhcyn02em.css';
import '../../css/l/l8_qf1bod.css';
import '../../css/f/fbsiz1bro.css';
import '../../css/t/tzbujjjnz.css';
import '../../css/k/kerkuuqkj.css';
import '../../css/m/m5beuq8ah.css';
import '../../css/b/bwrhq3b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="vhcyn02em"/><path class="l8_qf1bod"/><path class="fbsiz1bro"/><path class="tzbujjjnz"/><path class="kerkuuqkj"/><path class="m5beuq8ah"/><path class="bwrhq3b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:sk-4x3" /></template>
