<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8ugbvd9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i8ugbvd9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:message-tick-outline" /></template>
