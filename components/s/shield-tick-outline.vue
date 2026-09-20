<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbiu-lblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zbiu-lblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:shield-tick-outline" /></template>
