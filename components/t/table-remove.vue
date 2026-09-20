<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2nz88a_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2nz88a_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:table-remove" /></template>
