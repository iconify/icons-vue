<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpbsv3b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rpbsv3b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:msr" /></template>
