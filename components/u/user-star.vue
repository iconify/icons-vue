<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vutc8zb9c.css';
import '../../css/e/el0rrrluf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vutc8zb9c"/><path class="el0rrrluf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:user-star" /></template>
