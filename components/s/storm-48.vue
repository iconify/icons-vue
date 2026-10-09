<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyu8e9b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zyu8e9b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:storm-48" /></template>
