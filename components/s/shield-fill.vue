<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwuu_8brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dwuu_8brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:shield-fill" /></template>
