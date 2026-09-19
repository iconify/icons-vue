<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kebm7gbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kebm7gbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:team-work" /></template>
