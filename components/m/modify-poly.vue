<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/str33hb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="str33hb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:modify-poly" /></template>
