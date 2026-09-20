<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywm-p_b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ywm-p_b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:ram" /></template>
