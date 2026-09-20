<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezqm6lbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":48};
const content = `<path class="ezqm6lbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:water-bottle" /></template>
