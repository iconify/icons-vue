<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szahujb-p.css';
import '../../css/t/tat5f9buu.css';
import '../../css/i/ijzvcdc3l.css';
import '../../css/r/re21d5fjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="szahujb-p"/><path class="tat5f9buu"/><path class="ijzvcdc3l"/><path class="re21d5fjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:prescription-20" /></template>
