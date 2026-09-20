<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu0_pgdyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wu0_pgdyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:shield-x-outline" /></template>
