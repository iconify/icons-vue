<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmztj_bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gmztj_bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:suitcase" /></template>
