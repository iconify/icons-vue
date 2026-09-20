<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqhvoz1ft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqhvoz1ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mark-pen-fill" /></template>
