<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suk0u9b4j.css';
import '../../css/p/pf11sko1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="suk0u9b4j"/><path class="pf11sko1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-gibbous-20" /></template>
