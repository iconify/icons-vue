<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdams4bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="kdams4bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:office" /></template>
