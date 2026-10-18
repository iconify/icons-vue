<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9c7k7buf.css';
import '../../css/d/deqru1bcw.css';
import '../../css/r/r2g2ubnfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x9c7k7buf"/><path class="deqru1bcw"/><path class="r2g2ubnfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:park-and-ride-20" /></template>
