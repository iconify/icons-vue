<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibjd92y_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ibjd92y_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:plus-minus" /></template>
