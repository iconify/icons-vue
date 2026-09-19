<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx-8-ebcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qx-8-ebcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:person-fill" /></template>
