<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvch9ib1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="yvch9ib1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:unlocked" /></template>
