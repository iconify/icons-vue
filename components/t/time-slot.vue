<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n050cnbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n050cnbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:time-slot" /></template>
