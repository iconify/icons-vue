<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov5ht6eqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ov5ht6eqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:palete" /></template>
