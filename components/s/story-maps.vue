<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl3l4tb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="tl3l4tb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:story-maps" /></template>
