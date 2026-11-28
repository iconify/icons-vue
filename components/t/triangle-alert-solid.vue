<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz4xghbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz4xghbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:triangle-alert-solid" /></template>
