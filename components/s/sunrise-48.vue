<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-taz-bdu.css';
import '../../css/f/ftnl01noy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p-taz-bdu"/><path class="ftnl01noy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sunrise-48" /></template>
