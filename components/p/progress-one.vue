<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbftq4bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lbftq4bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:progress-one" /></template>
