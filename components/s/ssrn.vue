<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paf7zpi5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="paf7zpi5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ssrn" /></template>
