<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk0nhcbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="pk0nhcbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:polygon-o-dash" /></template>
