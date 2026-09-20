<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agzafq8wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="agzafq8wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:network" /></template>
