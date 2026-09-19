<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hak87y75g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hak87y75g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:option-key" /></template>
