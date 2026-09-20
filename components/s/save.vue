<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p31jd6bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p31jd6bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:save" /></template>
