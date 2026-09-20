<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeo5pg9kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oeo5pg9kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:margin-bottom" /></template>
