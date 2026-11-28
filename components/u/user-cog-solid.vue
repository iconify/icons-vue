<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9pbffbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9pbffbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:user-cog-solid" /></template>
