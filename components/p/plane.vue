<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvh9_ktkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="lvh9_ktkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:plane" /></template>
