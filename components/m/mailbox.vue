<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlqmsc7ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mlqmsc7ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:mailbox" /></template>
