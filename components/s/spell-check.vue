<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8l390kbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="s8l390kbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:spell-check" /></template>
