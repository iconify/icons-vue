<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0p10dgla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b0p10dgla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:quote" /></template>
