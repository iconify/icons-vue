<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le8sjw5jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="le8sjw5jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:stopwatch-filled" /></template>
