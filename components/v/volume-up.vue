<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-cu9tb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="q-cu9tb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:volume-up" /></template>
