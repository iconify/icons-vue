<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmw0aqb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wmw0aqb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:preregistered-de-tc-square" /></template>
