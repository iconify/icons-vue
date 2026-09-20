<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x67rembyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x67rembyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-in-water" /></template>
