<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-y-is37i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-y-is37i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-18-small" /></template>
