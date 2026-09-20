<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-jc7bb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-jc7bb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:personalcard-filled" /></template>
