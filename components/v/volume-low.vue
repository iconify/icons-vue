<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojw0e_9cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ojw0e_9cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:volume-low" /></template>
