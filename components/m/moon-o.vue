<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv_f63b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jv_f63b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:moon-o" /></template>
