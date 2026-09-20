<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3l7v_b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n3l7v_b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:stumbleupon-circle" /></template>
