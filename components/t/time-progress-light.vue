<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwtppab6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwtppab6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:time-progress-light" /></template>
