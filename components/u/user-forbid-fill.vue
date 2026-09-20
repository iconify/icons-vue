<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv4fbjbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv4fbjbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-forbid-fill" /></template>
