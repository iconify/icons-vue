<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z21-q0eyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z21-q0eyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:micro-sd" /></template>
