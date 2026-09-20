<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxqle7bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gxqle7bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:return-key" /></template>
