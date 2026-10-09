<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsy6m-bng.css';
import '../../css/j/j04z_-bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hsy6m-bng"/><path class="j04z_-bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:undo-20" /></template>
