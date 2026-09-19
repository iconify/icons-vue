<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um0m0ubvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um0m0ubvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:rocket-launch" /></template>
