<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psv830b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="psv830b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:shuffle" /></template>
