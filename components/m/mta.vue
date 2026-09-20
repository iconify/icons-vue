<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uym1rkb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uym1rkb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mta" /></template>
