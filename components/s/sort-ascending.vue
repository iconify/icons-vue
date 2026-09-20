<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md-ipomfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="md-ipomfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:sort-ascending" /></template>
