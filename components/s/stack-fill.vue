<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdn-cbc-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdn-cbc-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:stack-fill" /></template>
