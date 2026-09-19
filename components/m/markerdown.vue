<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx4kzbcrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="wx4kzbcrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:markerdown" /></template>
