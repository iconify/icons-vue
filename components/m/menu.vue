<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkwr88bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hkwr88bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:menu" /></template>
