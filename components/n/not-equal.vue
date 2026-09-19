<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2aou47wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="o2aou47wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:not-equal" /></template>
