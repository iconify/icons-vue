<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z53lt7bqm.css';
import '../../css/u/ul7690b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z53lt7bqm"/><path class="ul7690b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:text-color-20-bold" /></template>
