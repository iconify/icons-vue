<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w338884rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w338884rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:repeat-off" /></template>
