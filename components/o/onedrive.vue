<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy2q4fbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uy2q4fbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:onedrive" /></template>
