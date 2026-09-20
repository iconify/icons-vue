<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7ihovbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7ihovbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-92-small" /></template>
