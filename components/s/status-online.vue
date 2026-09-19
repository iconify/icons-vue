<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8s-9bcke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8s-9bcke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:status-online" /></template>
