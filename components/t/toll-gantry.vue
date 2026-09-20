<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju0-6kfns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ju0-6kfns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:toll-gantry" /></template>
