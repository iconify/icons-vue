<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pryjc9bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pryjc9bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pause-circle-fill" /></template>
