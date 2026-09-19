<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_4p6yb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k_4p6yb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:spinner5" /></template>
