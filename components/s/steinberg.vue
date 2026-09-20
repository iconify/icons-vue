<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np5colb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np5colb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:steinberg" /></template>
