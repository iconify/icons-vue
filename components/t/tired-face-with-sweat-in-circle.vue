<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5-mv2ddo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f5-mv2ddo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tired-face-with-sweat-in-circle" /></template>
