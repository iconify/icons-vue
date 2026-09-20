<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2a83kbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2a83kbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:quote-down-circle-filled" /></template>
