<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb5k4m7rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="mb5k4m7rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:rainbow" /></template>
