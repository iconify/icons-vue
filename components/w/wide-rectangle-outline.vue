<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsh-0cd-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hsh-0cd-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wide-rectangle-outline" /></template>
