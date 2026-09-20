<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odjw9lbqc.css';
import '../../css/n/nn95hacfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="odjw9lbqc"/><path class="nn95hacfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:records" /></template>
