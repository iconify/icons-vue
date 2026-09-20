<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8fq14a_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8fq14a_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:times-circle-solid" /></template>
