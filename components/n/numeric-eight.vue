<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byrp3ybsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byrp3ybsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-eight" /></template>
