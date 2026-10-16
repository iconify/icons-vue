<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_hltyb1h.css';
import '../../css/f/fvgea5bgo.css';
import '../../css/v/vmdmbbhtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s_hltyb1h"/><path class="fvgea5bgo"/><path class="vmdmbbhtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tokamak-20-bold" /></template>
