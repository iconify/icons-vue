<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od5se8z1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od5se8z1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tails" /></template>
