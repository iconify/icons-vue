<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qor1kflej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qor1kflej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:order-done-outline" /></template>
