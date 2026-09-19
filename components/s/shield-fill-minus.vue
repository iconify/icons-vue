<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhmj4mblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uhmj4mblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:shield-fill-minus" /></template>
