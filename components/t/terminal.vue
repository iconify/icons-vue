<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmx3q3erz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mmx3q3erz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:terminal" /></template>
