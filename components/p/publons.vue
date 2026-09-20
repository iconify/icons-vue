<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7ffc1bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7ffc1bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:publons" /></template>
