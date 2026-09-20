<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgv18hbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgv18hbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pleroma" /></template>
