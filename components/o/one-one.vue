<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reoap2bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="reoap2bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:one-one" /></template>
