<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0-5-9fnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x0-5-9fnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-in-stroke-16" /></template>
