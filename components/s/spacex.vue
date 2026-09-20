<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzij7bbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzij7bbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:spacex" /></template>
