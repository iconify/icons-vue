<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqaetjboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rqaetjboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:tamtam-16" /></template>
