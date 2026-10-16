<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3bu2g2no.css';
import '../../css/i/iyhbzwb_j.css';
import '../../css/y/yfoxxnbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m3bu2g2no"/><path class="iyhbzwb_j"/><path class="yfoxxnbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vertical-solar-20-bold" /></template>
