<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr3ix3wqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gr3ix3wqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:rocket-on-launch-pad" /></template>
