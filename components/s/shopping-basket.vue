<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw5lexb-j.css';
import '../../css/y/y4rdwmmfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw5lexb-j"/><path class="y4rdwmmfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:shopping-basket" /></template>
