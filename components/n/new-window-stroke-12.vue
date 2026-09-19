<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvmvosuww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tvmvosuww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:new-window-stroke-12" /></template>
