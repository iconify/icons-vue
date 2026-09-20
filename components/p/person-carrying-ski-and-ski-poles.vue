<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-fx9vqjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y-fx9vqjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-carrying-ski-and-ski-poles" /></template>
