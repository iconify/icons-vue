<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugqfnxbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugqfnxbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:monitor-refresh" /></template>
