<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urxdbibml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urxdbibml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:scopus" /></template>
