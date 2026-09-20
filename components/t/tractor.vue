<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-d5jcb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-d5jcb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tractor" /></template>
