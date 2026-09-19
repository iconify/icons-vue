<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty4atgz1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ty4atgz1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:shield" /></template>
