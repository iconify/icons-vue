<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc5qjjbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":472};
const content = `<path class="pc5qjjbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:sound-down" /></template>
