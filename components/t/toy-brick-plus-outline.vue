<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp-r0nz9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp-r0nz9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:toy-brick-plus-outline" /></template>
