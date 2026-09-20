<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq9tt3b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="yq9tt3b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:shield" /></template>
