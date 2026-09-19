<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl1i6hciw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vl1i6hciw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:p-circle-fill" /></template>
