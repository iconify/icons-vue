<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cydns6brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cydns6brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stairs-down" /></template>
