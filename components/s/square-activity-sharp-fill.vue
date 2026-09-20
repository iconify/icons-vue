<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m94-e1boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m94-e1boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-activity-sharp-fill" /></template>
