<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt537krfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt537krfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:rings" /></template>
