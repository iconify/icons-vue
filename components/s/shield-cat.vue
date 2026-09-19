<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtf0p8bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vtf0p8bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:shield-cat" /></template>
