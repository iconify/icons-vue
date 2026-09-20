<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chsjt2b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="chsjt2b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:paragraph-outline" /></template>
