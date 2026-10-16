<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlsr1qbum.css';
import '../../css/l/l59iq9btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mlsr1qbum"/><path class="l59iq9btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:water-butt-20-bold" /></template>
