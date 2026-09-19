<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozxj_jbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ozxj_jbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sun-fill" /></template>
