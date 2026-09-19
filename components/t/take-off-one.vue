<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlm0orbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qlm0orbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:take-off-one" /></template>
