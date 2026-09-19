<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osgzido7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="osgzido7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:umbrella" /></template>
