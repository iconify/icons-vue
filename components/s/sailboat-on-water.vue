<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hylio2wag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hylio2wag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sailboat-on-water" /></template>
