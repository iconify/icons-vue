<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlyd17xxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wlyd17xxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:margin-left" /></template>
