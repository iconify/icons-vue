<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-_it7bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-_it7bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:netflix" /></template>
