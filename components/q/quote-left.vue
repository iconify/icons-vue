<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcf9nvb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vcf9nvb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:quote-left" /></template>
