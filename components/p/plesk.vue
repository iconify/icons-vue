<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul_2399ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul_2399ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:plesk" /></template>
