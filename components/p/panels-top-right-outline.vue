<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q268_fbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q268_fbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-top-right-outline" /></template>
