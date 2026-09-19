<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5lh_qp0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k5lh_qp0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:order-server" /></template>
