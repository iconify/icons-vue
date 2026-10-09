<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdy4ipb5m.css';
import '../../css/s/swkeh7byr.css';
import '../../css/z/zjjlddhpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zdy4ipb5m"/><path class="swkeh7byr"/><path class="zjjlddhpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mooring-20-bold" /></template>
