<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-4gsqb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":24};
const content = `<path class="w-4gsqb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:steam" /></template>
