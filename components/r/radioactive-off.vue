<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbi5g97mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbi5g97mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:radioactive-off" /></template>
