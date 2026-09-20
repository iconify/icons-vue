<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmdv5sb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmdv5sb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:thumbs-down" /></template>
