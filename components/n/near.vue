<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x77kc5b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x77kc5b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:near" /></template>
