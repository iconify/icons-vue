<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3qe4db5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3qe4db5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:rectangle-stack" /></template>
