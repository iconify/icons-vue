<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-0a_5-7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v-0a_5-7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:pause-circle-fill" /></template>
