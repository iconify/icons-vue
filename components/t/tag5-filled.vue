<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihca-gn3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihca-gn3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tag5-filled" /></template>
