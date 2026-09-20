<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a79z4tb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a79z4tb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tally-four" /></template>
