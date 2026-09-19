<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8h_dobbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8h_dobbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:map" /></template>
