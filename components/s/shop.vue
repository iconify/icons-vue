<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq_wuqm-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="wq_wuqm-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:shop" /></template>
