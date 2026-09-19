<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oez7e4bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oez7e4bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:money-alt" /></template>
