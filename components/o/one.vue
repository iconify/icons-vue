<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw1f1pl0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gw1f1pl0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:one" /></template>
