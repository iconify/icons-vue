<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5seiobvq.css';
import '../../css/u/uwrgjpbhp.css';
import '../../css/r/rs71wsbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r5seiobvq"/><path class="uwrgjpbhp"/><path class="rs71wsbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mobile-charger-20" /></template>
