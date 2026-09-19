<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz1pvbcft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tz1pvbcft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:untag" /></template>
