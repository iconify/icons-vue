<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7yslabqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7yslabqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:microsoft-teams" /></template>
