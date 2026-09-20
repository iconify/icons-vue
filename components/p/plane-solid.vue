<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcw81gbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcw81gbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:plane-solid" /></template>
