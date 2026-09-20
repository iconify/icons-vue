<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg_756b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hg_756b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:walk" /></template>
