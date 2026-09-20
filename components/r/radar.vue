<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq8l94kmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq8l94kmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:radar" /></template>
