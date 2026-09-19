<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5h0oqbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5h0oqbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:refresh-cw" /></template>
