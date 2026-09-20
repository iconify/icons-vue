<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7hv9zkbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7hv9zkbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:registered-line" /></template>
