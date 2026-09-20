<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6m821bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v6m821bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:michigan" /></template>
