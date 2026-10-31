<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezpr1gb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezpr1gb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:puzzle-round" /></template>
