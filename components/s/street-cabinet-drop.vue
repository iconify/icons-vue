<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2l1x3bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b2l1x3bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:street-cabinet-drop" /></template>
