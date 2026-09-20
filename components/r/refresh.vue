<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjfk7kbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vjfk7kbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:refresh" /></template>
