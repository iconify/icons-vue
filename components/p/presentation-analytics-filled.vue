<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7o6iqeuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7o6iqeuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:presentation-analytics-filled" /></template>
