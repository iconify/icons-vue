<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0bcb7bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0bcb7bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:puzzle" /></template>
