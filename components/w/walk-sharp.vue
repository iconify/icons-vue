<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myubtaccl.css';
import '../../css/w/wzrscbbrd.css';
import '../../css/s/sz77vjbtt.css';
import '../../css/w/wgc76mb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="myubtaccl"/><path class="wzrscbbrd"/><path class="sz77vjbtt"/><circle class="wgc76mb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:walk-sharp" /></template>
