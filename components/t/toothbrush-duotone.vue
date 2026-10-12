<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lc5v3gbaq.css';
import '../../css/c/cust0bcyw.css';
import '../../css/y/yz1489b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lc5v3gbaq"/><path class="cust0bcyw"/><path class="yz1489b0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:toothbrush-duotone" /></template>
