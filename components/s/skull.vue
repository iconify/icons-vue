<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkc--sb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fkc--sb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:skull" /></template>
