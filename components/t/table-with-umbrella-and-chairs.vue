<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rukjgpvbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rukjgpvbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:table-with-umbrella-and-chairs" /></template>
