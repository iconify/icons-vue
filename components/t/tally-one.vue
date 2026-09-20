<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3-0rpbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3-0rpbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tally-one" /></template>
