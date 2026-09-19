<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_ud-v2xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p_ud-v2xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:vine" /></template>
