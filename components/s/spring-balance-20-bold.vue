<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqojcvb-w.css';
import '../../css/g/g64mwldzs.css';
import '../../css/b/bz5lwabqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mqojcvb-w"/><path class="g64mwldzs"/><path class="bz5lwabqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spring-balance-20-bold" /></template>
