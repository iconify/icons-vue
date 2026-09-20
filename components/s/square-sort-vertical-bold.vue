<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh048ubrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gh048ubrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-sort-vertical-bold" /></template>
