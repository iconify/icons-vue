<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7zo2_bea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v7zo2_bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:up-circle-outline" /></template>
