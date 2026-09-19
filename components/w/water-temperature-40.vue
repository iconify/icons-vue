<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em3iyfb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":448};
const content = `<path class="em3iyfb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:water-temperature-40" /></template>
