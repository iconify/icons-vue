<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d30o7nb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d30o7nb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:off" /></template>
