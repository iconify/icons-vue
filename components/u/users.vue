<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_y984b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b_y984b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:users" /></template>
