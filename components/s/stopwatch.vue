<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1glz3bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o1glz3bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:stopwatch" /></template>
