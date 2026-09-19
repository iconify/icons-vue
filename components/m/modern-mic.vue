<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gufucky0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gufucky0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:modern-mic" /></template>
