<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok5iyvbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ok5iyvbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:skiing-11" /></template>
