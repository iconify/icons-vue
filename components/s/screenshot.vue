<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uey1fclew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uey1fclew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:screenshot" /></template>
