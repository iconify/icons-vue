<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c38ur7vib.css';
import '../../css/f/fwwetn73i.css';
import '../../css/v/vu0y6dd0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c38ur7vib"/><path class="fwwetn73i"/><path class="vu0y6dd0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:steam-reformer-20" /></template>
