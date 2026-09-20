<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmekq-6-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmekq-6-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tally-one-solid" /></template>
