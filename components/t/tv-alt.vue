<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0bymlb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0bymlb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tv-alt" /></template>
