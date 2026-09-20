<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kke7zvbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kke7zvbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sort-ascending-2-filled" /></template>
