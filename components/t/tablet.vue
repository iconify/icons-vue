<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofi5qkbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofi5qkbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:tablet" /></template>
