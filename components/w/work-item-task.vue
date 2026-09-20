<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srezkwbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="srezkwbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:work-item-task" /></template>
