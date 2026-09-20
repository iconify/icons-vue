<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6f3q9nuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6f3q9nuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-location-line" /></template>
