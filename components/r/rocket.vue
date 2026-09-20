<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqibyvg5x.css';
import '../../css/w/wwyne7smp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iqibyvg5x"/><path class="wwyne7smp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:rocket" /></template>
