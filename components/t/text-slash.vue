<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk9o850it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk9o850it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:text-slash" /></template>
