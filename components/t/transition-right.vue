<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7qn3oxgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7qn3oxgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:transition-right" /></template>
