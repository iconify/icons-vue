<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt9rm4bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1344};
const content = `<path class="mt9rm4bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:timeslot" /></template>
