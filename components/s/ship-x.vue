<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu2gylbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu2gylbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ship-x" /></template>
