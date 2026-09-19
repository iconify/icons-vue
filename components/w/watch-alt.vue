<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n23vf1bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n23vf1bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:watch-alt" /></template>
