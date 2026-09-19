<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc1aw7qal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nc1aw7qal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:network" /></template>
