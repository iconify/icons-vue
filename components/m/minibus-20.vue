<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miccwacuq.css';
import '../../css/g/gtqceqbja.css';
import '../../css/f/f8wc0fbln.css';
import '../../css/y/yf8odfm8j.css';
import '../../css/r/ra3z0j7ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="miccwacuq"/><path class="gtqceqbja"/><path class="f8wc0fbln"/><path class="yf8odfm8j"/><path class="ra3z0j7ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:minibus-20" /></template>
