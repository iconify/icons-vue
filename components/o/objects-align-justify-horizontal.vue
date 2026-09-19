<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h36_oubov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h36_oubov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:objects-align-justify-horizontal" /></template>
