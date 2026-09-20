<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lverkgpfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lverkgpfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:stop" /></template>
