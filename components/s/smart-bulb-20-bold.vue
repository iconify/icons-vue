<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thnh47bcs.css';
import '../../css/f/fuhaovbal.css';
import '../../css/t/t1nxsq_lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="thnh47bcs"/><path class="fuhaovbal"/><path class="t1nxsq_lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-bulb-20-bold" /></template>
