<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhjziobee.css';
import '../../css/q/q7z1euqgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qhjziobee"/><path class="q7z1euqgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:male" /></template>
