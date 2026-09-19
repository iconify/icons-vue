<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8unnac5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i8unnac5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:volume-medium-outline" /></template>
