<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv4icwedh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv4icwedh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:squircle" /></template>
