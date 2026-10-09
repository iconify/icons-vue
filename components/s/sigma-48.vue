<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw2pwjbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pw2pwjbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sigma-48" /></template>
