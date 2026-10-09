<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjw5bmbkb.css';
import '../../css/g/gy2b850nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vjw5bmbkb"/><path class="gy2b850nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:map-20" /></template>
