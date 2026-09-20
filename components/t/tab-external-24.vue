<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-lz6bbgg.css';
import '../../css/f/fewj64b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-lz6bbgg"/><path class="fewj64b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:tab-external-24" /></template>
