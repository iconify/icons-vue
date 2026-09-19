<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4k6q8q-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4k6q8q-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tally-2" /></template>
