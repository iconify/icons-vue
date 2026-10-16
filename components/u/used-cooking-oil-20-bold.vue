<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ammh8jlyd.css';
import '../../css/i/iux9rx_ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ammh8jlyd"/><path class="iux9rx_ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:used-cooking-oil-20-bold" /></template>
