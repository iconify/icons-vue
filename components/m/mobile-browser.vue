<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irnp2otqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="irnp2otqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:mobile-browser" /></template>
