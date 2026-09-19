<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejwi4yg8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ejwi4yg8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:plane-circle-xmark" /></template>
