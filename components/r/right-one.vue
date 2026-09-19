<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1wjytbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w1wjytbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:right-one" /></template>
