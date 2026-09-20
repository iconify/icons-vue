<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwh4ec31y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwh4ec31y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:maximize-off" /></template>
